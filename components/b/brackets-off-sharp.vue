<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk76ikbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk76ikbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:brackets-off-sharp" /></template>
