<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_rdqn7gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="p_rdqn7gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:diamond-duo" /></template>
