<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysamgs33o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysamgs33o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:check-thick" /></template>
