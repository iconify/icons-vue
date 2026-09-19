<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1i1pzulb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l1i1pzulb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:check-circle-fill" /></template>
