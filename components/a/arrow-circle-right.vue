<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tug4wjebt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tug4wjebt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:arrow-circle-right" /></template>
