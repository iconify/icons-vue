<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lyq5oz7xh.css';
import '../../css/a/aa91s4kim.css';
import '../../css/e/e9041zbna.css';
import '../../css/g/g66c9lb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lyq5oz7xh"/><path clip-rule="evenodd" class="aa91s4kim"/><path class="e9041zbna"/><path clip-rule="evenodd" class="g66c9lb7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:envelope-front-outline" /></template>
