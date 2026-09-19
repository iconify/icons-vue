<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljt949bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ljt949bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:contrast" /></template>
