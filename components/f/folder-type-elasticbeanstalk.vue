<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mspevbqol"/><path class="bwgzqdmaz"/><path class="qhuslxbzr"/><path class="w39n61bgs"/><path class="hg9enk90p"/><path class="dcs0jhmkk"/><path class="sonf8mugx"/><path class="i_qeidc3d"/><path class="a-g33hb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-elasticbeanstalk" /></template>
<style>
.a-g33hb_l {
  fill: var(--svg-color--f58536, #f58536);
  d: path("m21.998 22.921l-4.842.535v4.409l4.842-1.299z");
}

.bwgzqdmaz {
  fill: var(--svg-color--9d5025, #9d5025);
  d: path("M20.8 11.3v9.2h-1.07v8.665L23.4 31l2.217-10.5L23.4 10z");
}

.dcs0jhmkk {
  fill: var(--svg-color--9d5025, #9d5025);
  d: path("m24.802 18.079l4.842-.535v-4.409l-4.842 1.299z");
}

.hg9enk90p {
  fill: var(--svg-color--f58536, #f58536);
  d: path("m29.644 13.135l1.325.662v4.027l-1.325-.28z");
}

.i_qeidc3d {
  fill: var(--svg-color--9d5025, #9d5025);
  d: path("m17.156 27.865l-1.325-.662v-4.027l1.325.28z");
}

.mspevbqol {
  fill: var(--svg-color--c17e53, #c17e53);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

.qhuslxbzr {
  fill: var(--svg-color--f58536, #f58536);
  d: path("M23.4 10v21l2.6-1.3v-9.2h1.07v-8.665z");
}

.sonf8mugx {
  fill: var(--svg-color--fbbf93, #fbbf93);
  d: path("m15.831 23.176l4.638-.433l1.529.178l-4.842 4.944z");
}

.w39n61bgs {
  fill: var(--svg-color--6b3a19, #6b3a19);
  d: path("m30.969 17.824l-4.638.433l-1.529-.178l4.842-4.944z");
}

</style>
