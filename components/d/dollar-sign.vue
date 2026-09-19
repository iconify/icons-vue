<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixtgx4b_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ixtgx4b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:dollar-sign" /></template>
