<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmba4taom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="lmba4taom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:calendar-check" /></template>
