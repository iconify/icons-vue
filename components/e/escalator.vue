<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0nxcnbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0nxcnbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:escalator" /></template>
