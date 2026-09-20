<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe5lb9btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fe5lb9btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:information-desk-remix" /></template>
