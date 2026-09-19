<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0xvj0b_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v0xvj0b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:contact-book" /></template>
