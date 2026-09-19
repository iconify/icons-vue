<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qup63mb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qup63mb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:circle-half" /></template>
