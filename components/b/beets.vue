<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx3nz_bus.css';
import '../../css/n/ndo424b7h.css';
import '../../css/q/q8jig3bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rx3nz_bus"/><path class="ndo424b7h"/><path class="q8jig3bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beets" /></template>
