<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drltkhb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="drltkhb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:list-add" /></template>
