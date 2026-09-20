<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xowvf-_hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xowvf-_hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:home-sharp" /></template>
