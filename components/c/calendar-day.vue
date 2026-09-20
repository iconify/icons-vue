<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_uxkxb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="z_uxkxb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:calendar-day" /></template>
