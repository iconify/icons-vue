<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/nw14a-bbp.css';
import '../../css/e/e6qicfbfp.css';
import '../../css/s/syvz2ggnb.css';
import '../../css/k/kz0_pvboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="nw14a-bbp"/><path class="e6qicfbfp"/><path class="syvz2ggnb"/><path class="kz0_pvboy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ellipsis-circle-outline" /></template>
