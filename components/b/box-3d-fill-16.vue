<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9975k8sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p9975k8sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:box-3d-fill-16" /></template>
