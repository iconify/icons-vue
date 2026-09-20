<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mth0oeb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mth0oeb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:data-file-graph-bold" /></template>
