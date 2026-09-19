<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql5xq868z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ql5xq868z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:calendar-clear-sharp" /></template>
