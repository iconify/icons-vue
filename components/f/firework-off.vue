<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_u8rob9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_u8rob9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:firework-off" /></template>
