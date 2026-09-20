<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh-4570hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qh-4570hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:drop-down-menu-remix" /></template>
