<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vige47nfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vige47nfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-fill-round" /></template>
