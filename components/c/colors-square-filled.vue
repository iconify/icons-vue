<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcuq4bbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcuq4bbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:colors-square-filled" /></template>
