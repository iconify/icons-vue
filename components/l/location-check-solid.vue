<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty2v0klct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty2v0klct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:location-check-solid" /></template>
