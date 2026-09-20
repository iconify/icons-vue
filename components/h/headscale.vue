<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acky41bit.css';
import '../../css/s/sfa1rc65h.css';
import '../../css/r/rt2xw8--p.css';
import '../../css/b/bo8_cj02q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="acky41bit"/><path class="sfa1rc65h"/><path class="rt2xw8--p"/><path class="bo8_cj02q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:headscale" /></template>
