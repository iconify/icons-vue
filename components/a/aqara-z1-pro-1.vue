<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xepbup7xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xepbup7xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-z1-pro-1" /></template>
