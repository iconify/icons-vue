<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr7womf9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kr7womf9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:face-sad-stroke-12" /></template>
