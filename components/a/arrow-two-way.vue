<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik5cx86xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="ik5cx86xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-two-way" /></template>
