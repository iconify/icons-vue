<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5mtn7z9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5mtn7z9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:export" /></template>
