<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-01g7bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e-01g7bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:beach-solid" /></template>
