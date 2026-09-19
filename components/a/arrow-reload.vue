<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my91cbcgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="my91cbcgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-reload" /></template>
