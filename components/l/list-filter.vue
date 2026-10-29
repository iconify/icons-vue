<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol_y8tkuq.css';
import '../../css/e/eorjg-5_x.css';
import '../../css/e/ectew4bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol_y8tkuq wm-shadow"/><path class="eorjg-5_x wm-k"/><path class="ectew4bwb wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:list-filter" /></template>
