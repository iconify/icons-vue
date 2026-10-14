<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0tvb20ai.css';
import '../../css/r/r1hiqbchs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x0tvb20ai"/><path class="r1hiqbchs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:healthlog-light" /></template>
