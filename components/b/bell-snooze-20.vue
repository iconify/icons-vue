<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhcjdtn8d.css';
import '../../css/l/l8_-m635t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yhcjdtn8d"/><path class="l8_-m635t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-snooze-20" /></template>
