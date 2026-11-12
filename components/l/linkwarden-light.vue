<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i--9t9r5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i--9t9r5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linkwarden-light" /></template>
