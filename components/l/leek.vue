<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd2r_wbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd2r_wbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:leek" /></template>
