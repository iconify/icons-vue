<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8ntsyb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u8ntsyb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:layers" /></template>
