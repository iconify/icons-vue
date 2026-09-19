<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml8l45bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="ml8l45bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bottle-water" /></template>
