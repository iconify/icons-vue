<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz5d-qbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="lz5d-qbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:lungs-virus" /></template>
