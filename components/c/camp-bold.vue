<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl7j8ub1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hl7j8ub1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:camp-bold" /></template>
