<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh1uod04j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="eh1uod04j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:j-duo" /></template>
