<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os4wsf10g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="os4wsf10g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:droplet" /></template>
