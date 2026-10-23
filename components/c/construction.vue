<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ripm6yrej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ripm6yrej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:construction" /></template>
