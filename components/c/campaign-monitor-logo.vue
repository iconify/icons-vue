<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzhlgjbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzhlgjbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:campaign-monitor-logo" /></template>
