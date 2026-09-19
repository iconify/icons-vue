<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x61k8684r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x61k8684r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cc-square-fill" /></template>
