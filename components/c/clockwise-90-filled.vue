<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg99jbc7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wg99jbc7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:clockwise-90-filled" /></template>
