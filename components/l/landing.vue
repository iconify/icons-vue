<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_s9z448p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p_s9z448p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:landing" /></template>
