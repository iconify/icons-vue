<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl2f_dlbg.css';
import '../../css/e/erolj7bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jl2f_dlbg"/><path class="erolj7bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ironcalc-light" /></template>
