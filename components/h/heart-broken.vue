<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orxt2w0nn.css';
import '../../css/y/ys2g1yc6p.css';
import '../../css/n/n4j_19b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="orxt2w0nn"/><path class="ys2g1yc6p"/><path class="n4j_19b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:heart-broken" /></template>
