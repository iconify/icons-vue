<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es9laet0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="es9laet0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bone" /></template>
