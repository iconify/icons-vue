<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp42q063p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sp42q063p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hospital-symbol2x-outline" /></template>
