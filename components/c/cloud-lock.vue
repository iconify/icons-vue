<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgrv538an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgrv538an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-lock" /></template>
