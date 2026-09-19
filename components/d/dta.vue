<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ups_s6b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ups_s6b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:dta" /></template>
