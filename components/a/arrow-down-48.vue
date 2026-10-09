<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df1n7oboy.css';
import '../../css/d/dp3euwb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="df1n7oboy"/><path class="dp3euwb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-down-48" /></template>
