<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1mcems0k.css';
import '../../css/r/rtxe8yjtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1mcems0k"/><path class="rtxe8yjtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-thermometer-20-bold" /></template>
