<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asc-prbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asc-prbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:edit-box-line" /></template>
