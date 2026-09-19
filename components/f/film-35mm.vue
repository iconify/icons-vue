<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsx39kbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bsx39kbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:film-35mm" /></template>
