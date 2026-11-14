<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4lni4bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:golf-putter" /></template>
<style>
.n4lni4bgc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.896 15.75l2.342-13.118q.027-.147-.005-.293q-.032-.145-.118-.268q-.085-.122-.211-.203q-.125-.08-.272-.106q-.073-.013-.147-.012q-.074.002-.146.017t-.14.046q-.067.029-.128.072q-.06.042-.112.095q-.051.053-.091.116q-.039.062-.066.131q-.027.068-.04.141l-2.39 13.382H7.25q-3 0-3 3t3 3h9.5q3 0 3-3t-3-3z");
}

</style>
