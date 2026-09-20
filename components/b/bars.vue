<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wem5me46l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wem5me46l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bars" /></template>
