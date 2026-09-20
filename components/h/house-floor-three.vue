<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axwp7cbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axwp7cbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-floor-three" /></template>
