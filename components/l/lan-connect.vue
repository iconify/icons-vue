<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvso-p9wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvso-p9wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lan-connect" /></template>
