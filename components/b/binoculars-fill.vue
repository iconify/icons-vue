<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz14ndrgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fz14ndrgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:binoculars-fill" /></template>
