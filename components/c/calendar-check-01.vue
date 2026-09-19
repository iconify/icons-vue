<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovon6wixu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovon6wixu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calendar-check-01" /></template>
