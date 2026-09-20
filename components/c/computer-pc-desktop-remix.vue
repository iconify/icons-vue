<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn6bwj6xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gn6bwj6xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:computer-pc-desktop-remix" /></template>
