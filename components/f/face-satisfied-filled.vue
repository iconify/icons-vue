<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugr3mblsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ugr3mblsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:face-satisfied-filled" /></template>
