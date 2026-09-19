<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkiso9bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkiso9bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-sun-rain" /></template>
