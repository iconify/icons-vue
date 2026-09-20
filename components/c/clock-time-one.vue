<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il5vivbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il5vivbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-time-one" /></template>
