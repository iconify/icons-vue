<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/engu9tz6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="engu9tz6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:droplet-solid" /></template>
