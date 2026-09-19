<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7q-v7b5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="v7q-v7b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:hamburger" /></template>
