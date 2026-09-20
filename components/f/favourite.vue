<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfc8sf6fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfc8sf6fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:favourite" /></template>
