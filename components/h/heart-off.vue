<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa1n06c0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa1n06c0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heart-off" /></template>
