<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4nr2k08r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4nr2k08r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:blinds" /></template>
