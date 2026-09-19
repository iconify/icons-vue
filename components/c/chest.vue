<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsm4ve1hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nsm4ve1hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:chest" /></template>
