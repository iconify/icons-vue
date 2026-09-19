<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um7oh2ecr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="um7oh2ecr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:hand" /></template>
