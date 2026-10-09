<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh7ndob2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wh7ndob2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:list-checks-48-bold" /></template>
