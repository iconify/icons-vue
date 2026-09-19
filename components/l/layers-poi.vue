<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9tbpdr2g.css';
import '../../css/t/tf2al91ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="k9tbpdr2g"/><path class="tf2al91ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layers-poi" /></template>
