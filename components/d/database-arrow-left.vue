<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtkvy1_xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="vtkvy1_xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:database-arrow-left" /></template>
