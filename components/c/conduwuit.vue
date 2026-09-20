<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4goj5bvt.css';
import '../../css/y/yrj6_5bgi.css';
import '../../css/d/d83egmi4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w4goj5bvt"/><path class="yrj6_5bgi"/><path class="d83egmi4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:conduwuit" /></template>
