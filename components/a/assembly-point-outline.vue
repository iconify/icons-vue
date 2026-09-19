<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otf6voeig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="otf6voeig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:assembly-point-outline" /></template>
