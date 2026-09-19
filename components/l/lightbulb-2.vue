<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbb2bw7jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="lbb2bw7jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:lightbulb-2" /></template>
