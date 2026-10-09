<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekbu-fbrm.css';
import '../../css/x/x_ur3irsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ekbu-fbrm"/><path class="x_ur3irsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-range-20-bold" /></template>
