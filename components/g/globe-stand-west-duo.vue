<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k12za_xqk.css';
import '../../css/r/r6wv3sbay.css';
import '../../css/b/b9c3bg9mh.css';
import '../../css/p/p0lznmxvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="k12za_xqk"/><path class="r6wv3sbay"/><path class="b9c3bg9mh"/><path class="p0lznmxvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-stand-west-duo" /></template>
