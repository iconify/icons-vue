<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf5ppncjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf5ppncjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:crosshair-solid" /></template>
