<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_iv7psnh.css';
import '../../css/r/rlhcac1kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer y_iv7psnh"/><path class="duoicon-primary-layer rlhcac1kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:box" /></template>
