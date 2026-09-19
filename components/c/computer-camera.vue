<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h76a9ql5h.css';
import '../../css/i/i5o3gv_dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer h76a9ql5h"/><path class="duoicon-secondary-layer i5o3gv_dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:computer-camera" /></template>
