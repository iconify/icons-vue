<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iso5s1bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iso5s1bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:album-line" /></template>
