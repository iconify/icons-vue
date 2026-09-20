<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ung_ne2kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ung_ne2kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:flash-1" /></template>
