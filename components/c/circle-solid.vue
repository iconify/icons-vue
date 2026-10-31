<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdg7vccce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xdg7vccce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:circle-solid" /></template>
