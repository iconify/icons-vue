<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa8xxfbmy.css';
import '../../css/s/sms_5zbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wa8xxfbmy"/><path class="sms_5zbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:copy" /></template>
