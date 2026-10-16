<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg12-u1eb.css';
import '../../css/t/tzz4r4bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jg12-u1eb"/><path class="tzz4r4bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-moon-rain-20-bold" /></template>
