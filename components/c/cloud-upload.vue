<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zynbnac3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="zynbnac3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:cloud-upload" /></template>
