<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbkt2actg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gbkt2actg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:distribute-horizontal-20-bold" /></template>
