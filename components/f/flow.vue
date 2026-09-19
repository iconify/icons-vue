<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiu6qlb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":413,"height":512};
const content = `<path class="wiu6qlb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:flow" /></template>
