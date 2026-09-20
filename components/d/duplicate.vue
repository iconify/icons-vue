<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tni8dxx4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tni8dxx4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:duplicate" /></template>
