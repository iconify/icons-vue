<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0e2_bc4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="f0e2_bc4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:church" /></template>
