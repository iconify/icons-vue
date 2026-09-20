<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg567jbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vg567jbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:loading-circle-solid" /></template>
