<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-km8rbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="l-km8rbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:arrow-right-circle-1-solid" /></template>
