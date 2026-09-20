<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmvyxybqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qmvyxybqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:laundry-14" /></template>
