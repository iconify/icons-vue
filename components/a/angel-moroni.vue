<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxnef4b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nxnef4b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:angel-moroni" /></template>
