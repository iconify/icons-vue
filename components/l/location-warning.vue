<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv7cs-bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv7cs-bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:location-warning" /></template>
