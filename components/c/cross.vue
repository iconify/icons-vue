<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d41kdhboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d41kdhboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:cross" /></template>
