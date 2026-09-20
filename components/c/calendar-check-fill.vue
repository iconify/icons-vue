<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn7p-dbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn7p-dbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:calendar-check-fill" /></template>
