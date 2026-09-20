<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yak4y02xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yak4y02xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-pilot-outline" /></template>
