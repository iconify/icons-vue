<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez__yk4iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ez__yk4iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:calculator-2" /></template>
