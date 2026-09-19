<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg-sl6llt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mg-sl6llt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-merge" /></template>
