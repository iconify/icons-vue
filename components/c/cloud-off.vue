<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1yr61btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1yr61btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloud-off" /></template>
