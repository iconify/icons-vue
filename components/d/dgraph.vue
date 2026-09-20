<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qic13w4zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qic13w4zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dgraph" /></template>
