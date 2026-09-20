<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd2lk3b2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd2lk3b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bell-ring" /></template>
