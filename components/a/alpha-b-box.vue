<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plvifacdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plvifacdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-b-box" /></template>
