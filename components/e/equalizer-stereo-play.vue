<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/cdqi89uqz.css';
import '../../css/f/fnpz7hl0i.css';
import '../../css/a/au6mv_ewn.css';
import '../../css/f/f4x0cwtqd.css';
import '../../css/u/u6ejn4b7d.css';
import '../../css/j/jtl23jtof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="cdqi89uqz"/><path class="fnpz7hl0i"/><path class="au6mv_ewn"/><path class="f4x0cwtqd"/><path class="u6ejn4b7d"/><path class="jtl23jtof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:equalizer-stereo-play" /></template>
