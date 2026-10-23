<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4r4-xbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q4r4-xbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:high-temp-outline" /></template>
