<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmmx76bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmmx76bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-rain-sun" /></template>
