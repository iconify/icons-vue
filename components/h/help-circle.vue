<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl5uzhbhz.css';
import '../../css/d/d48x1gbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl5uzhbhz wm-k"/><path class="d48x1gbyl wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:help-circle" /></template>
