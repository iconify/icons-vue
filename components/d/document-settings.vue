<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccb5m9byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ccb5m9byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:document-settings" /></template>
