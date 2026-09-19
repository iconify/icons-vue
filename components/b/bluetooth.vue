<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5619jkwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="a5619jkwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:bluetooth" /></template>
