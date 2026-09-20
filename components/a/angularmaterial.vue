<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2ub9vb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="f2ub9vb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:angularmaterial" /></template>
