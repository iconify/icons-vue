<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf-ujzx2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1664};
const content = `<path class="wf-ujzx2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:gitlab" /></template>
