<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg48uhzxf.css';
import '../../css/i/i-gh0uunf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dg48uhzxf"/><path class="i-gh0uunf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:elk" /></template>
