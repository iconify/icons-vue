<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rptwl7fjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rptwl7fjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-gemini-dark" /></template>
