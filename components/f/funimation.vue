<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6jl-3b4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":612,"height":90.8,"top":350.6};
const content = `<path class="f6jl-3b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:funimation" /></template>
