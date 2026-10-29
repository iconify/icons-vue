<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbk7k8bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbk7k8bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:app-window" /></template>
