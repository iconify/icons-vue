<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la-8prbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="la-8prbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:batterysixty" /></template>
