<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1toveb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q1toveb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:immich-light" /></template>
