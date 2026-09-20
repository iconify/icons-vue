<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om7wr648a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om7wr648a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-p" /></template>
