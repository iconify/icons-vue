<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dymvktbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dymvktbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:emlakjet" /></template>
