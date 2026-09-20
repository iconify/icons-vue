<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etn01zbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="etn01zbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:circle-stop-filled" /></template>
