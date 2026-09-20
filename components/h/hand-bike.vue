<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm_-v1bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm_-v1bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-bike" /></template>
