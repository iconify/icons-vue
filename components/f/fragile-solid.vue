<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6gk6tkiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e6gk6tkiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:fragile-solid" /></template>
