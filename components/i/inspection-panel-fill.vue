<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqz_x-bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqz_x-bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:inspection-panel-fill" /></template>
