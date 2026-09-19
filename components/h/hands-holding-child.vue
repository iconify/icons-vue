<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1r5mhbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="x1r5mhbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hands-holding-child" /></template>
