<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm6z-nwnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm6z-nwnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-variant-outline" /></template>
