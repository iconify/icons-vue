<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl70dwxfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nl70dwxfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:controller-1-solid" /></template>
