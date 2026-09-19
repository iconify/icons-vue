<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_d4skbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="o_d4skbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:crown-outline" /></template>
