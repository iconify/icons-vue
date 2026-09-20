<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n56ae_bgb.css';
import '../../css/j/jigbsmb_n.css';
import '../../css/l/l2vhs6x9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n56ae_bgb"/><path class="jigbsmb_n"/><path class="l2vhs6x9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:diskover" /></template>
