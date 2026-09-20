<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsm7hzbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsm7hzbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:access-point-off" /></template>
