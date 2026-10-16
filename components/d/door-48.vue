<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wifw4mbzo.css';
import '../../css/j/j5rik_bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wifw4mbzo"/><path class="j5rik_bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:door-48" /></template>
