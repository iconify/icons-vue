<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxkwk3bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxkwk3bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:egg-crack-line" /></template>
