<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1zs8h7wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1zs8h7wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chart-gantt-solid" /></template>
