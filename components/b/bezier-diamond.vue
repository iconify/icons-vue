<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9lmjhb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="e9lmjhb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bezier-diamond" /></template>
