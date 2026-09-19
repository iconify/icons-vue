<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kycc8uldy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kycc8uldy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-down" /></template>
