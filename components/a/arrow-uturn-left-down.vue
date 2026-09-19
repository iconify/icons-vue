<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1fq_zfjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m1fq_zfjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-uturn-left-down" /></template>
