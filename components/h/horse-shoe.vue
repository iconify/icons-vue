<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek__51g7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="ek__51g7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:horse-shoe" /></template>
