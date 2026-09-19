<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgbapyxqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bgbapyxqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:lightbulb-1" /></template>
