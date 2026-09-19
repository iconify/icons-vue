<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr--ilbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="yr--ilbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:lock-unlock" /></template>
