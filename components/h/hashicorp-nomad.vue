<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3bpc5bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d3bpc5bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-nomad" /></template>
