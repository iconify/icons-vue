<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s99b1cbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s99b1cbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-minus-outline" /></template>
