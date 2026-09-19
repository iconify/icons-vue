<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzjfxccab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kzjfxccab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:lactation" /></template>
