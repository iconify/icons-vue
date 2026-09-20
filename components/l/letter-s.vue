<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7-hg3k7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7-hg3k7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-s" /></template>
