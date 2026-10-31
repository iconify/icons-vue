<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8e-g6_ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8e-g6_ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:align-justify" /></template>
