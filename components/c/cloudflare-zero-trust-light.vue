<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlfva0b0l.css';
import '../../css/o/oouf8iqje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jlfva0b0l"/><path class="oouf8iqje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudflare-zero-trust-light" /></template>
