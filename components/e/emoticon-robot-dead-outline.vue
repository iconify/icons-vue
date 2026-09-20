<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clgw4qbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clgw4qbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoticon-robot-dead-outline" /></template>
