<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we_rnnwsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="we_rnnwsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:die" /></template>
