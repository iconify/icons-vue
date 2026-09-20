<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0rpfbf2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t0rpfbf2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:alarm-bell-cancelled-filled" /></template>
