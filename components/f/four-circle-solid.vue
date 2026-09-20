<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y29uzyclu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y29uzyclu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:four-circle-solid" /></template>
