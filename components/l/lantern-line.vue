<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly0yury_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly0yury_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lantern-line" /></template>
