<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_hiasb3j.css';
import '../../css/z/zme2kfuvy.css';
import '../../css/j/joilwmbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i_hiasb3j"/><path class="zme2kfuvy"/><path class="joilwmbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cement-plant-20-bold" /></template>
