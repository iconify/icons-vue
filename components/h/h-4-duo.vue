<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfij4xb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="kfij4xb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-4-duo" /></template>
