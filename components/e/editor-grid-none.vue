<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-f5jnbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m-f5jnbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:editor-grid-none" /></template>
