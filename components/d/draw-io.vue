<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aktiaydcc.css';
import '../../css/c/c20n45bfn.css';
import '../../css/c/czv5jnbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aktiaydcc"/><path class="c20n45bfn"/><path class="czv5jnbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:draw-io" /></template>
