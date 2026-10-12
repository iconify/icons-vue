<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gozz3nbxj.css';
import '../../css/m/mwkd_0bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gozz3nbxj"/><path class="mwkd_0bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:acorn-20-bold" /></template>
