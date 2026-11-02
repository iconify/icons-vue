<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvoblgb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvoblgb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alarm-2-fill" /></template>
