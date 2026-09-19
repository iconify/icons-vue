<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrwdudb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nrwdudb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-down-from-line" /></template>
