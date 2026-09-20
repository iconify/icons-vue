<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb658b_kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bb658b_kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-y-square-solid" /></template>
