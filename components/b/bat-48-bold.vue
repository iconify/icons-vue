<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biumr4bgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="biumr4bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bat-48-bold" /></template>
