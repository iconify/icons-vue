<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-wkm2f6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-wkm2f6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:heavy-showers-line" /></template>
