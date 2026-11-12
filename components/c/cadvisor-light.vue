<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq7p2zb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sq7p2zb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cadvisor-light" /></template>
