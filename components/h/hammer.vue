<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw4-4_bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="uw4-4_bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hammer" /></template>
