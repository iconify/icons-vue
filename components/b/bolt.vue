<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s11qicbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="s11qicbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bolt" /></template>
