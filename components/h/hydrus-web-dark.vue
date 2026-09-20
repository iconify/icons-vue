<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqd6bpb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qqd6bpb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hydrus-web-dark" /></template>
