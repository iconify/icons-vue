<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp83pzo0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fp83pzo0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bicycle-3" /></template>
