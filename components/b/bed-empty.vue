<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km5ljjbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="km5ljjbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bed-empty" /></template>
