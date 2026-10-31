<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp4k5yfan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp4k5yfan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:apple-fill-round" /></template>
