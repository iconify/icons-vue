<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3rz52jnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="w3rz52jnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:basket-bold" /></template>
