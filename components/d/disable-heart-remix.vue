<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbew85u1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cbew85u1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:disable-heart-remix" /></template>
