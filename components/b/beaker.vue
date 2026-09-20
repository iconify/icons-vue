<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2zdqcbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x2zdqcbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:beaker" /></template>
