<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uguz04bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uguz04bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:attachment-tick" /></template>
