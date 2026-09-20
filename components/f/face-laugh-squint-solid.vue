<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjuo1cbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjuo1cbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:face-laugh-squint-solid" /></template>
