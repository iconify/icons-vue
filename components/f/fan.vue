<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my0dy7qzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my0dy7qzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fan" /></template>
