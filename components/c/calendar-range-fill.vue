<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbn8dlkys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbn8dlkys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-range-fill" /></template>
