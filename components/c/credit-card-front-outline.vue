<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cwb3ucp-y.css';
import '../../css/b/buk4bs-bz.css';
import '../../css/m/my7k74b0k.css';
import '../../css/l/l2-6kbirp.css';
import '../../css/n/neryn4z-j.css';
import '../../css/e/ejy3vgbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="cwb3ucp-y"/><path class="buk4bs-bz"/><path clip-rule="evenodd" class="my7k74b0k"/><path clip-rule="evenodd" class="l2-6kbirp"/><path class="neryn4z-j"/><path clip-rule="evenodd" class="ejy3vgbvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:credit-card-front-outline" /></template>
