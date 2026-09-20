<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjui_cb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjui_cb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:calendar-edit-1-bold" /></template>
