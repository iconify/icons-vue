<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi0vm5zlg.css';
import '../../css/w/w5p8r3ckd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1547,"height":2503};
const content = `<path class="pi0vm5zlg"/><path class="w5p8r3ckd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dassault-aviation" /></template>
