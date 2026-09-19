<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqx9-3d1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqx9-3d1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:frame-bold" /></template>
