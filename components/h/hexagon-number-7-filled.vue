<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkon9widq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkon9widq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-number-7-filled" /></template>
