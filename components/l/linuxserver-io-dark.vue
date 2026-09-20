<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe_izbisr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xe_izbisr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linuxserver-io-dark" /></template>
