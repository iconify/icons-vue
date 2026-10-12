<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4ifueief.css';
import '../../css/v/v2yg3bceh.css';
import '../../css/w/w762ysbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s4ifueief"/><path class="v2yg3bceh"/><path class="w762ysbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blood-drop-48-bold" /></template>
