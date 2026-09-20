<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajpcoobkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajpcoobkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heart-minus" /></template>
