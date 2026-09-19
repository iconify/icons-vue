<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb0hm5tda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="vb0hm5tda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:euro" /></template>
