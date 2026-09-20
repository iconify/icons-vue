<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hssyr4yeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hssyr4yeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-desktop-up" /></template>
