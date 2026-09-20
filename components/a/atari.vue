<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orini3b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orini3b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:atari" /></template>
