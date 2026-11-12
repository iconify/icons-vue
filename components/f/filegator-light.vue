<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceyh5fb6m.css';
import '../../css/l/lktrzctrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ceyh5fb6m"/><path class="lktrzctrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filegator-light" /></template>
