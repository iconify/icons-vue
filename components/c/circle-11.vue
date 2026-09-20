<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1gq_obxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f1gq_obxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:circle-11" /></template>
