<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f53r9-bns.css';
import '../../css/b/bge442bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f53r9-bns"/><path class="bge442bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fedex" /></template>
