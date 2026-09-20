<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es5s-vbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="es5s-vbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:bell" /></template>
