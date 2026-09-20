<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5e_cby5o.css';
import '../../css/t/tncgtrlau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m5e_cby5o"/><path class="tncgtrlau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:android-auto-dark" /></template>
