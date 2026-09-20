<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv9y7lbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rv9y7lbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:layout-window-4" /></template>
