<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljdd0lbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ljdd0lbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:log" /></template>
