<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w08-fwv8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w08-fwv8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloud-moon-rain" /></template>
