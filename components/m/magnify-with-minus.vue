<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy58e45_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zy58e45_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:magnify-with-minus" /></template>
