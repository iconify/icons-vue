<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhfbthbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="fhfbthbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:feather" /></template>
