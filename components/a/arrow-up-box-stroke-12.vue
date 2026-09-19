<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fns4x3b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fns4x3b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-up-box-stroke-12" /></template>
