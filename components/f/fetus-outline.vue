<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irfh52bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="irfh52bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:fetus-outline" /></template>
