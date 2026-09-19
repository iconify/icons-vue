<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awu1eodbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="awu1eodbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:jsfiddle" /></template>
