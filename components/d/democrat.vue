<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf56pcb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kf56pcb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:democrat" /></template>
