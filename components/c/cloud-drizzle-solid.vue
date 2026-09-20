<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6k3adcvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6k3adcvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloud-drizzle-solid" /></template>
