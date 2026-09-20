<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-zmqpb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l-zmqpb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calibre-web-dark" /></template>
