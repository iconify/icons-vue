<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybq7s_syt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybq7s_syt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-forced-mode" /></template>
