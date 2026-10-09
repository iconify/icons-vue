<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1mcems0k.css';
import '../../css/d/ddxx92y4s.css';
import '../../css/a/ampqdu6-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1mcems0k"/><path class="ddxx92y4s"/><path class="ampqdu6-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-battery-20-bold" /></template>
