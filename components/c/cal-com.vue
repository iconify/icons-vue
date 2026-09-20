<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrjsy3seb.css';
import '../../css/f/fc0sbw29e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vrjsy3seb"/><path class="fc0sbw29e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cal-com" /></template>
