<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz0bm-2uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz0bm-2uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-refresh" /></template>
