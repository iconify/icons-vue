<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu71tbcjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu71tbcjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-wireless-40" /></template>
