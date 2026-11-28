<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o65e3xbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o65e3xbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:calendar-sparkles-solid" /></template>
