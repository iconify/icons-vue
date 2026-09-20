<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do5qysy-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do5qysy-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:hospital-sign-bold" /></template>
