<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzrmc7i5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="mzrmc7i5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:eye-slash-outline" /></template>
