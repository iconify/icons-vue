<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbtb55bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dbtb55bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:downtify-light" /></template>
