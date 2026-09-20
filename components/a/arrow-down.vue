<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcxe_wboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":16};
const content = `<path class="lcxe_wboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-down" /></template>
