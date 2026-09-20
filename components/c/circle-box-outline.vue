<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap0-habhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap0-habhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:circle-box-outline" /></template>
