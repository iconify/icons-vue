<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl2mnppab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="xl2mnppab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:clipboard" /></template>
