<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqk5i7b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqk5i7b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ice-cream-line" /></template>
