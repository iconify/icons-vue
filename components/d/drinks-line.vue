<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vicy7ngor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vicy7ngor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:drinks-line" /></template>
