<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i632_abrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i632_abrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:backpack-gloss" /></template>
