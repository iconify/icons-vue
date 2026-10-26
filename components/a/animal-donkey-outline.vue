<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh4nadbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hh4nadbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:animal-donkey-outline" /></template>
