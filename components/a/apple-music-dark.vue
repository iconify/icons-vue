<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5i7l73zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j5i7l73zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apple-music-dark" /></template>
