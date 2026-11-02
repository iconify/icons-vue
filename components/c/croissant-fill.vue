<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q28vt0hbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q28vt0hbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:croissant-fill" /></template>
