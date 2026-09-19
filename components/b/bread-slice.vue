<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj2_z7fcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fj2_z7fcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:bread-slice" /></template>
