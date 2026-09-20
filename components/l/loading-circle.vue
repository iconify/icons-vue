<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mthucvbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mthucvbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:loading-circle" /></template>
