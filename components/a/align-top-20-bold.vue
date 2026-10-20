<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_320w4ee.css';
import '../../css/e/ec0kd2kjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u_320w4ee"/><path class="ec0kd2kjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-top-20-bold" /></template>
