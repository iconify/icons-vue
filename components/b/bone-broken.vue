<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n97-l2bar.css';
import '../../css/b/b94xtzblu.css';
import '../../css/b/b7iizbs3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="n97-l2bar"/><path class="b94xtzblu"/><path clip-rule="evenodd" class="b7iizbs3o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bone-broken" /></template>
