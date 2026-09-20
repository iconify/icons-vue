<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpr-1rm3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpr-1rm3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:keyboard-solid" /></template>
