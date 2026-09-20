<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8vtk2bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8vtk2bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layout-dashboard-fill" /></template>
