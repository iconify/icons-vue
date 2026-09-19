<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in1u28j_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="in1u28j_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:briefcase" /></template>
