<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldso4pdyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ldso4pdyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:calendar-mirrored" /></template>
