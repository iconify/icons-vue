<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j56_aob9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j56_aob9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-arrow-right" /></template>
