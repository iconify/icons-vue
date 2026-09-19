<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlzlh4b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mlzlh4b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:graduation-cap" /></template>
