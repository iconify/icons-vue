<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koehhbc9o.css';
import '../../css/w/wqypsdb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="koehhbc9o"/><path class="wqypsdb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kiroshi" /></template>
