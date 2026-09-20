<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waf5nr0aw.css';
import '../../css/f/flc22bblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="waf5nr0aw"/><path class="flc22bblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filesync" /></template>
