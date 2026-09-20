<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebz01bbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ebz01bbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:home" /></template>
