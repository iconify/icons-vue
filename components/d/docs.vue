<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en_nqv76t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="en_nqv76t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:docs" /></template>
