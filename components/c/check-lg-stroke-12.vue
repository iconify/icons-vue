<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb0t6_b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cb0t6_b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-lg-stroke-12" /></template>
