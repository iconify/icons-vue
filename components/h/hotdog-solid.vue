<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o76mt6y5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o76mt6y5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hotdog-solid" /></template>
