<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcyw3wb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pcyw3wb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-plus-fill" /></template>
