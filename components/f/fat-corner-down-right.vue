<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6o3xdrfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6o3xdrfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-corner-down-right" /></template>
