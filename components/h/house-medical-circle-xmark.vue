<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzggoov-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pzggoov-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:house-medical-circle-xmark" /></template>
