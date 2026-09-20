<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aebd-tbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aebd-tbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-off-outline" /></template>
