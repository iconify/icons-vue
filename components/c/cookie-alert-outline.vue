<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hezl8sbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hezl8sbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cookie-alert-outline" /></template>
