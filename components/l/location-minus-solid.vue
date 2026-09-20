<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkcz61e6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkcz61e6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:location-minus-solid" /></template>
