<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj_2eeb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pj_2eeb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:heart-cardiogram" /></template>
