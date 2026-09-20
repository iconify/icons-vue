<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs1d7sbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xs1d7sbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:half-star-2-flat" /></template>
