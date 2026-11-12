<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8g050_hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h8g050_hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linuxserver-io-light" /></template>
