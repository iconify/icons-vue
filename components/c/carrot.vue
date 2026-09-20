<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmwn_mb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmwn_mb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:carrot" /></template>
