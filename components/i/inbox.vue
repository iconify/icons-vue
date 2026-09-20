<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb9-9z58s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb9-9z58s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:inbox" /></template>
