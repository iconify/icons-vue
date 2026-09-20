<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_dovporp.css';
import '../../css/r/rc7tgcbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d_dovporp"/><path class="rc7tgcbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:airpipe" /></template>
