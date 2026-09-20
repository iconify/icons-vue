<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qll5a5f5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qll5a5f5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:komga-light" /></template>
