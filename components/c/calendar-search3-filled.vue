<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gisz0600z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gisz0600z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calendar-search3-filled" /></template>
