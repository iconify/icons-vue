<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls34a7bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ls34a7bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:house-medical-circle-exclamation" /></template>
