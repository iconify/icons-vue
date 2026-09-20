<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-fyg8bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-fyg8bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:label-multiple-outline" /></template>
