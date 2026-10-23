<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkq-4jiie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkq-4jiie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:drafting-compass" /></template>
