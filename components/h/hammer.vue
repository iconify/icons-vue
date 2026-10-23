<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na311lbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na311lbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:hammer" /></template>
