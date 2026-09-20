<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezqrlfave.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":16};
const content = `<path class="ezqrlfave"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bold" /></template>
