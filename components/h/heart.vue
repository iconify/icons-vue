<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug98l9j0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ug98l9j0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:heart" /></template>
