<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti120ucnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ti120ucnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-2" /></template>
