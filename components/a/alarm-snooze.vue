<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ectql4bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ectql4bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alarm-snooze" /></template>
