<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl59arb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jl59arb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linear-dark" /></template>
