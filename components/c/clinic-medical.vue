<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3m213b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t3m213b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:clinic-medical" /></template>
