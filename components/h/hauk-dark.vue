<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp2bmljol.css';
import '../../css/i/i7dds8b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kp2bmljol"/><path class="i7dds8b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hauk-dark" /></template>
