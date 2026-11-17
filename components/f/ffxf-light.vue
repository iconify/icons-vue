<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7o1kib7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q7o1kib7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ffxf-light" /></template>
