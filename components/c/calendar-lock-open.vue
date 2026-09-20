<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn-2qlb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn-2qlb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-lock-open" /></template>
