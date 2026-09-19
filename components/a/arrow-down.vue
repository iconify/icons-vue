<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s66i86wmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s66i86wmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:arrow-down" /></template>
