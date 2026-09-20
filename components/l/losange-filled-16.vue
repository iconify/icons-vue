<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhyb4abqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yhyb4abqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:losange-filled-16" /></template>
