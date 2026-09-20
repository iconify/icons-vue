<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyht5ccdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyht5ccdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-x-circle" /></template>
