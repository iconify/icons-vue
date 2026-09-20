<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrh5_9blm.css';
import '../../css/s/s4f0-m1sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rrh5_9blm"/><path class="s4f0-m1sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:continuwuity-dark" /></template>
