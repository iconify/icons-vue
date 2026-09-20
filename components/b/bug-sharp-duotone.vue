<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/d/d67d1o37r.css';
import '../../css/n/nbgaetwkj.css';
import '../../css/i/ix6zqj6-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="d67d1o37r"/><path class="nbgaetwkj"/><path clip-rule="evenodd" class="ix6zqj6-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bug-sharp-duotone" /></template>
