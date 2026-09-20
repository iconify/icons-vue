<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeubzac7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oeubzac7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-diving" /></template>
