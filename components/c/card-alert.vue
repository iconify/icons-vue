<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln51mfiyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="ln51mfiyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:card-alert" /></template>
