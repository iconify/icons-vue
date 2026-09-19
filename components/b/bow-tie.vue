<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhd610b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="dhd610b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bow-tie" /></template>
