<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lctqtk5pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="lctqtk5pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:code" /></template>
