<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1wu8bb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="j1wu8bb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-upward" /></template>
