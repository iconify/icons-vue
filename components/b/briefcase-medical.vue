<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn36-5bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xn36-5bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:briefcase-medical" /></template>
