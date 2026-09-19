<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sym2kf7vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sym2kf7vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:building-fill-16" /></template>
