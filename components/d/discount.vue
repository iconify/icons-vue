<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by7gwpbho.css';
import '../../css/p/pnb1asb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by7gwpbho duoicon-secondary-layer"/><path class="duoicon-primary-layer pnb1asb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:discount" /></template>
