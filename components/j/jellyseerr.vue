<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkb3lbbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkb3lbbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:jellyseerr" /></template>
