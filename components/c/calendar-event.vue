<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix75i-bma.css';
import '../../css/m/m5m_kacnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix75i-bma"/><path class="m5m_kacnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:calendar-event" /></template>
