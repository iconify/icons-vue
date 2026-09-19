<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siikb1s6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="siikb1s6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:animal-spider" /></template>
