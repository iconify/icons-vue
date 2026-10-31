<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwqsjcb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwqsjcb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-days-round" /></template>
