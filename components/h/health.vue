<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6o7ekkbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x6o7ekkbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:health" /></template>
