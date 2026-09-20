<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozgm-tbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ozgm-tbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gandi-light" /></template>
