<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1m0fhbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m1m0fhbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:align-txt-right-outline" /></template>
