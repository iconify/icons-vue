<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-5rh9o_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u-5rh9o_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:banknote-stack-in-slot" /></template>
