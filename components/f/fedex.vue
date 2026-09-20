<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f53r9-bns.css';
import '../../css/h/hutz5yftv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f53r9-bns"/><path class="hutz5yftv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fedex" /></template>
