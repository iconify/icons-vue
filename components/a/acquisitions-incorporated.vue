<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j84lrp6hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="j84lrp6hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:acquisitions-incorporated" /></template>
