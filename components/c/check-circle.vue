<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw96a2bzf.css';
import '../../css/m/mjs2czbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer gw96a2bzf"/><path class="duoicon-primary-layer mjs2czbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:check-circle" /></template>
