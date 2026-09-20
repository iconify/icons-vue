<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruef20b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="ruef20b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-right" /></template>
