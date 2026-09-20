<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_xc13bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="k_xc13bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:grocery-11" /></template>
