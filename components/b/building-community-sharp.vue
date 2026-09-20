<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm43ot0wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm43ot0wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:building-community-sharp" /></template>
