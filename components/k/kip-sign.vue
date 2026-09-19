<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuw2e-bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fuw2e-bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:kip-sign" /></template>
