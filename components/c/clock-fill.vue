<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfvh-zmer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfvh-zmer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-fill" /></template>
