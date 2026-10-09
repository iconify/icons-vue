<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faw1_xb-c.css';
import '../../css/d/dyv57sbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="faw1_xb-c"/><path class="dyv57sbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fusion-48" /></template>
