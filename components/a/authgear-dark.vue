<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki-0lmrvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ki-0lmrvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:authgear-dark" /></template>
