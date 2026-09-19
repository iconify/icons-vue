<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-h9r1mla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p-h9r1mla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:factory" /></template>
