<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlrw7obei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="mlrw7obei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:dice-5" /></template>
