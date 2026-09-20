<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct11--kks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ct11--kks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:arrow-transfer-horizontal-square-solid" /></template>
