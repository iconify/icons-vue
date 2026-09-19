<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrokb7bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zrokb7bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:circle-half-outline" /></template>
