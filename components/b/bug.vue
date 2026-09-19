<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8v63iu0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h8v63iu0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bug" /></template>
