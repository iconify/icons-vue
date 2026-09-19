<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmajru3gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="nmajru3gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:jump-page-left-right" /></template>
