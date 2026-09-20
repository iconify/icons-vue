<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4fpidhjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s4fpidhjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amurex-light" /></template>
