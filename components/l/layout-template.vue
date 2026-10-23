<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fju_5jblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fju_5jblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layout-template" /></template>
