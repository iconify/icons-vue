<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7pghdblc.css';
import '../../css/d/ddhwi2bsr.css';
import '../../css/z/zi6wn-bta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="l7pghdblc"/><path class="ddhwi2bsr"/><path class="zi6wn-bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:location-poi-o" /></template>
