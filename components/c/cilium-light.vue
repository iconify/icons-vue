<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opw2n6p2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="opw2n6p2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cilium-light" /></template>
