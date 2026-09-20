<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2_e8rc4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q2_e8rc4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lyft" /></template>
