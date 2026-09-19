<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lch49bcjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lch49bcjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-uturn-right-up" /></template>
