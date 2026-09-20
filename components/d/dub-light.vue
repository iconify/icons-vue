<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmu-53b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tmu-53b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dub-light" /></template>
