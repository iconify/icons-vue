<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq7-tmb6k.css';
import '../../css/t/tofm4bbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hq7-tmb6k"/><rect class="tofm4bbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:besucherlogin-light" /></template>
