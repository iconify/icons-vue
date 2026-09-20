<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvo5yb4jk.css';
import '../../css/d/d5k0bgbry.css';
import '../../css/s/s4f0-m1sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="yvo5yb4jk"/><path class="d5k0bgbry"/><path class="s4f0-m1sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:continuwuity" /></template>
