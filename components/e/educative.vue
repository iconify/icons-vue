<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx2s7_b9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx2s7_b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:educative" /></template>
