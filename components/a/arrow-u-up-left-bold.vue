<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwxp3gbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwxp3gbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-u-up-left-bold" /></template>
