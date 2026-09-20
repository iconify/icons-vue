<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5yc--bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l5yc--bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:board-trolleybus" /></template>
