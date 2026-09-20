<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkn9-fbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkn9-fbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:app-store-line" /></template>
