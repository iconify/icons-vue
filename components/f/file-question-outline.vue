<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhig7ybyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhig7ybyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-question-outline" /></template>
