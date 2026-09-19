<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxjk7zwzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hxjk7zwzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:a2x-outline" /></template>
