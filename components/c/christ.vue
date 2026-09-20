<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stjril7pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="stjril7pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:christ" /></template>
