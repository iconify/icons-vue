<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxfg4pqzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pxfg4pqzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:lock-check" /></template>
