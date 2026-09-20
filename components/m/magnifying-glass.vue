<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_6i1t2sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="p_6i1t2sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:magnifying-glass" /></template>
