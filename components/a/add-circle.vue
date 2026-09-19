<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw96a2bzf.css';
import '../../css/p/p_cxci5xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer gw96a2bzf"/><path class="duoicon-primary-layer p_cxci5xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:add-circle" /></template>
