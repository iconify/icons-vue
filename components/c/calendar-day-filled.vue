<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb_pfbb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tb_pfbb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:calendar-day-filled" /></template>
