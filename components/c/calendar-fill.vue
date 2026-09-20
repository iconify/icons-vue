<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8ha5ackr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8ha5ackr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:calendar-fill" /></template>
