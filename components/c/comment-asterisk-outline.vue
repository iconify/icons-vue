<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s7g8mqb5w.css';
import '../../css/h/h7e86bbxn.css';
import '../../css/w/w_zdecccl.css';
import '../../css/w/wpe_c3oqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="s7g8mqb5w"/><path clip-rule="evenodd" class="h7e86bbxn"/><path class="w_zdecccl"/><path clip-rule="evenodd" class="wpe_c3oqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-asterisk-outline" /></template>
