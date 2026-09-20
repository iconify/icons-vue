<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvg7ngq4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvg7ngq4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:copy-filled" /></template>
