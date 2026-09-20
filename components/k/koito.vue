<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgrj4e4gu.css';
import '../../css/x/xpheglbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rgrj4e4gu"/><path class="xpheglbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:koito" /></template>
