<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp0257bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="mp0257bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:book-open" /></template>
