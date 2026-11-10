<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgtjx7byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgtjx7byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-arrow-path" /></template>
