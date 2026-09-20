<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjw2c-b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rjw2c-b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kali-linux-wordmark" /></template>
