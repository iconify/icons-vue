<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cezbknaez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cezbknaez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bookmark-snooze-solid" /></template>
