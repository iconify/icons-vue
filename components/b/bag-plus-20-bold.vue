<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg1pd4bom.css';
import '../../css/o/o9u2ibbix.css';
import '../../css/l/llirq21ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kg1pd4bom"/><path class="o9u2ibbix"/><path class="llirq21ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bag-plus-20-bold" /></template>
