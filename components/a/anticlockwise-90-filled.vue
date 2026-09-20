<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1zqgbula.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z1zqgbula"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:anticlockwise-90-filled" /></template>
