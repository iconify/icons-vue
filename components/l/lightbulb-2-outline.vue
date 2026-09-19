<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr8nz_b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tr8nz_b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:lightbulb-2-outline" /></template>
