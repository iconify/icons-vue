<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1pnusqee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="n1pnusqee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:cloud-data-transfer-remix" /></template>
