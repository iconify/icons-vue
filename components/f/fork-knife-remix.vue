<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0mg5_20h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z0mg5_20h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:fork-knife-remix" /></template>
