<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu9am2bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu9am2bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloudy" /></template>
