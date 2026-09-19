<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh0bafb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nh0bafb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:extension-puzzle-sharp" /></template>
