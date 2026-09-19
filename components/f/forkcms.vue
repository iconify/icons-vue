<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pll558mvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":896};
const content = `<path class="pll558mvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:forkcms" /></template>
