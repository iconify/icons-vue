<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_y7o7b0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t_y7o7b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-mp4-filled" /></template>
