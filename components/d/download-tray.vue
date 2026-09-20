<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1f2vmboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="r1f2vmboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:download-tray" /></template>
