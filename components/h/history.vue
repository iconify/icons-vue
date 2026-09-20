<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dehqt92jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="dehqt92jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:history" /></template>
