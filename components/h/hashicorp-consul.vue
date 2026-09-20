<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foypfgb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="foypfgb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-consul" /></template>
