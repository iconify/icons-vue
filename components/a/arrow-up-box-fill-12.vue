<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5_j0fbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="g5_j0fbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-up-box-fill-12" /></template>
