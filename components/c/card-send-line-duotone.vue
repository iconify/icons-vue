<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i9s-s9bxy.css';
import '../../css/u/uwaa3xb6z.css';
import '../../css/v/vqfns1bta.css';
import '../../css/b/baxqrnb6h.css';
import '../../css/j/j-a1kqp-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i9s-s9bxy"/><path class="uwaa3xb6z"/><path class="vqfns1bta"/><path class="baxqrnb6h"/><path class="j-a1kqp-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-send-line-duotone" /></template>
