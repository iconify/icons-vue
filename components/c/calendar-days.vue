<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zovczcbsn.css';
import '../../css/g/g_ku85bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zovczcbsn"/><path class="g_ku85bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:calendar-days" /></template>
