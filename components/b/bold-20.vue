<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5fb9gbyc.css';
import '../../css/m/mpi65j14y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i5fb9gbyc"/><path class="mpi65j14y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bold-20" /></template>
