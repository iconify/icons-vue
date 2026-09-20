<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pck1mgbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pck1mgbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bell-off" /></template>
