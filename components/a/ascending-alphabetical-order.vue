<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz32iacsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pz32iacsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ascending-alphabetical-order" /></template>
