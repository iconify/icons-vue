<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccp8libao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccp8libao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:die-4" /></template>
