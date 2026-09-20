<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvk743d6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mvk743d6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:immich-power-tools-light" /></template>
