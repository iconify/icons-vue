<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnfagub0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnfagub0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:calendar-question-mark-fill" /></template>
