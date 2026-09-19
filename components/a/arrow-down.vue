<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyz25t6vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oyz25t6vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-down" /></template>
