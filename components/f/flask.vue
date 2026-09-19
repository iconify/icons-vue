<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-lf7acey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="o-lf7acey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:flask" /></template>
