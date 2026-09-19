<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_ot34bbd.css';
import '../../css/q/qbu68misp.css';
import '../../css/d/dq9knjb2v.css';
import '../../css/g/gchs6_bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="e_ot34bbd"/><path class="qbu68misp"/><path class="dq9knjb2v"/><path class="gchs6_bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:fastify-wordmark" /></template>
