<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl5kyeu5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pl5kyeu5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:fahrenheit-remix" /></template>
