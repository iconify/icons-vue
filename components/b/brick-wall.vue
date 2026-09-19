<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_n5p1bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f_n5p1bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:brick-wall" /></template>
