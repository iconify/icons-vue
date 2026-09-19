<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv1v87bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="dv1v87bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:frog" /></template>
