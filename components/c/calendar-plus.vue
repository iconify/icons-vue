<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq6x3_7zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq6x3_7zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-plus" /></template>
