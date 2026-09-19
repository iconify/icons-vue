<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiv9lxbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tiv9lxbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:dash-fill-16" /></template>
