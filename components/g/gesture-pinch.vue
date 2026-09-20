<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l33nqq3_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l33nqq3_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gesture-pinch" /></template>
