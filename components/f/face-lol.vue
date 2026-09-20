<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2blecc3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2blecc3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:face-lol" /></template>
