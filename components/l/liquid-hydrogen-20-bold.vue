<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huaseya6u.css';
import '../../css/v/va_wj3nkc.css';
import '../../css/l/l05rrsb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="huaseya6u"/><path class="va_wj3nkc"/><path class="l05rrsb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:liquid-hydrogen-20-bold" /></template>
