<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvb6lmb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pvb6lmb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-counterclockwise" /></template>
