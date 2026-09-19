<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4jsp-bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="n4jsp-bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:house-medical-circle-check" /></template>
