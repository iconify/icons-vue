<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg1pd4bom.css';
import '../../css/v/vqn056b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kg1pd4bom"/><path class="vqn056b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bag-check-20-bold" /></template>
