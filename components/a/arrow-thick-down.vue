<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr9euzbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="lr9euzbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-thick-down" /></template>
