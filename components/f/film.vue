<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1n6s1bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w1n6s1bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:film" /></template>
