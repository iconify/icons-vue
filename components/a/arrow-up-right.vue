<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odyvstn9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odyvstn9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-right" /></template>
