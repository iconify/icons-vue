<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdqw21o2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hdqw21o2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cpap-masks-outline" /></template>
