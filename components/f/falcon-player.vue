<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g225s7bhh.css';
import '../../css/l/lqs3it20u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g225s7bhh"/><path class="lqs3it20u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:falcon-player" /></template>
