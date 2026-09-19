<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xusadys6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xusadys6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:devices-4" /></template>
