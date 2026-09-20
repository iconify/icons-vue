<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kevvj2bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kevvj2bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-i-square-solid" /></template>
