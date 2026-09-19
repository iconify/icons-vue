<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzqqceb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzqqceb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calendar-04" /></template>
