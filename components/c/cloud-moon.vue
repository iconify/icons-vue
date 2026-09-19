<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkqhd_div.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="tkqhd_div"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:cloud-moon" /></template>
