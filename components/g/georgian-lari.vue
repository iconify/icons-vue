<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opbdrbc-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opbdrbc-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:georgian-lari" /></template>
