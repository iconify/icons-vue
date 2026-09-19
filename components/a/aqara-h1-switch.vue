<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzp2s1bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzp2s1bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-h1-switch" /></template>
