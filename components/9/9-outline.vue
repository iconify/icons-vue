<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t90_9xbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t90_9xbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:9-outline" /></template>
