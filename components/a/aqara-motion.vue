<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_9j5hebv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_9j5hebv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-motion" /></template>
