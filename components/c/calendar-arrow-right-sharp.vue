<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xddbcbb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xddbcbb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-arrow-right-sharp" /></template>
