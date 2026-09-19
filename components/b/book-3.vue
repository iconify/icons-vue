<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bak2f201c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="bak2f201c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:book-3" /></template>
