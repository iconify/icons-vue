<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-epz3bkk.css';
import '../../css/e/eb9ww44oc.css';
import '../../css/g/gz2q0nbvi.css';
import '../../css/k/k3jd9cbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="f-epz3bkk"/><path class="eb9ww44oc"/><path clip-rule="evenodd" class="gz2q0nbvi"/><path class="k3jd9cbhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:helicopter-outline" /></template>
