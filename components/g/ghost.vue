<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nveg2nboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="nveg2nboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:ghost" /></template>
