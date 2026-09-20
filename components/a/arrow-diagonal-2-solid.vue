<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpffbdjyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cpffbdjyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:arrow-diagonal-2-solid" /></template>
