<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk21khipp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tk21khipp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:loaf-of-bread-above-outstretched-hand" /></template>
