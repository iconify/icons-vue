<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv3x2zbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="gv3x2zbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:calendar-close" /></template>
