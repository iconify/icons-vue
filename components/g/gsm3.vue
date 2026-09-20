<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw-pwm7xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sw-pwm7xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:gsm3" /></template>
