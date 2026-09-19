<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcau_ibpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lcau_ibpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:angle-down" /></template>
