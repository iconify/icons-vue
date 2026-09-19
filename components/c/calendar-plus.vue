<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge9gbalhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge9gbalhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calendar-plus" /></template>
