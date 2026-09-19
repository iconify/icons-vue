<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0-7q3b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d0-7q3b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:light-rain" /></template>
