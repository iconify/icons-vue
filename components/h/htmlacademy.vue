<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns030dt4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ns030dt4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:htmlacademy" /></template>
