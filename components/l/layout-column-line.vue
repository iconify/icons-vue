<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuptu_q2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuptu_q2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-column-line" /></template>
