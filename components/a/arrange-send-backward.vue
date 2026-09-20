<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd9m3dh5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd9m3dh5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrange-send-backward" /></template>
