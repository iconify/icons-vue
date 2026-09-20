<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyo_37bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="uyo_37bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:chevron-left" /></template>
