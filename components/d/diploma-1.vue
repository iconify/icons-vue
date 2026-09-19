<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri9ji-5tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ri9ji-5tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:diploma-1" /></template>
