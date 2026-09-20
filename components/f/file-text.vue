<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncgybacjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncgybacjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-text" /></template>
