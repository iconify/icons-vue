<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygk6s-8dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygk6s-8dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:brackets-off" /></template>
