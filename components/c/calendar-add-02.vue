<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbm-gwbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbm-gwbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calendar-add-02" /></template>
