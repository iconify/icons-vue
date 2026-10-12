<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai0frwm-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ai0frwm-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:funnel-fill-20" /></template>
