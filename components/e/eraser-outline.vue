<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0gsoobto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o0gsoobto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eraser-outline" /></template>
