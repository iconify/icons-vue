<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_g4grbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u_g4grbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:commercial" /></template>
