<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skg5yh4xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skg5yh4xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-open-outline" /></template>
