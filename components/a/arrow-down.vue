<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-lctwb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="o-lctwb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:arrow-down" /></template>
