<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wje8iccmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wje8iccmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:arrow-turn-down-large-flat" /></template>
