<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq2grfbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq2grfbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:circle-arrows-off" /></template>
