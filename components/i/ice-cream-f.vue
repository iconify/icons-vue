<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4xm48b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-2};
const content = `<path class="g4xm48b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:ice-cream-f" /></template>
