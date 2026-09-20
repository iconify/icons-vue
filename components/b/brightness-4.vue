<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipw1llb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipw1llb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:brightness-4" /></template>
