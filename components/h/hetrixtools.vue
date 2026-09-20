<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7lf_dbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w7lf_dbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hetrixtools" /></template>
