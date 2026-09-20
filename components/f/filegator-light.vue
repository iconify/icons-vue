<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni6u1e5mh.css';
import '../../css/l/lktrzctrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ni6u1e5mh"/><path class="lktrzctrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filegator-light" /></template>
