<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl_ucd3ba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl_ucd3ba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cart" /></template>
