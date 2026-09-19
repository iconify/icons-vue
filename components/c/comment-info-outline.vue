<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bylw7jbya.css';
import '../../css/x/xm929l28t.css';
import '../../css/e/ec85-rcyc.css';
import '../../css/i/i5iq5xaql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bylw7jbya"/><path clip-rule="evenodd" class="xm929l28t"/><path class="ec85-rcyc"/><path clip-rule="evenodd" class="i5iq5xaql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-info-outline" /></template>
