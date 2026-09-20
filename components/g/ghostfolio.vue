<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxiw3kkvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxiw3kkvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ghostfolio" /></template>
