<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvefw0bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvefw0bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-time-three-outline" /></template>
