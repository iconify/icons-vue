<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvrsq3era.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="cvrsq3era"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:head-side-cough-slash" /></template>
