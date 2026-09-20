<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz01wxnsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz01wxnsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heart-remove" /></template>
