<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjjtffbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hjjtffbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:dribbble-with-circle" /></template>
