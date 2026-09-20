<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1h51eboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1h51eboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gitlab" /></template>
