<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwjpj5yee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwjpj5yee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:low-beam-headlights-fill" /></template>
