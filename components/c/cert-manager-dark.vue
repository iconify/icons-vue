<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7h0fccwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d7h0fccwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cert-manager-dark" /></template>
