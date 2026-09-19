<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_jv-6uof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="n_jv-6uof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-call-outline" /></template>
