<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljtdt-iiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljtdt-iiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-drop-circle-outline" /></template>
