<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_yb-6bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_yb-6bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-x-mark-solid" /></template>
