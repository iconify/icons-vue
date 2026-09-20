<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lah38-bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lah38-bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kopia" /></template>
