<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8wyu3a9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8wyu3a9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:camera-pet" /></template>
