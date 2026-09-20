<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlkvmfbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlkvmfbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:lightning" /></template>
