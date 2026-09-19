<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/raz481oyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="raz481oyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:fast-forward" /></template>
