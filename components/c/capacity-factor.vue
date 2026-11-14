<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gica_j02s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:capacity-factor" /></template>
<style>
.gica_j02s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 5q0-2.75 2.75-2.75T9.75 5T7 7.75T4.25 5m13.755-1.445l-11 10q-.111.1-.251.151t-.29.043t-.284-.071t-.235-.173q-.1-.111-.151-.251t-.043-.29q.007-.149.071-.284t.173-.235l11-10q.055-.05.118-.088q.064-.038.133-.063q.07-.025.143-.036t.147-.007t.145.021t.139.05q.066.031.126.075q.059.044.109.098t.088.118t.063.133t.036.143t.007.147q-.003.073-.021.145t-.05.139q-.031.066-.075.126q-.044.059-.098.109M17 8.25q-2.75 0-2.75 2.75T17 13.75T19.75 11T17 8.25m-3.75 13.5h5.5q3 0 3-3t-3-3h-5.5q3 0 3 3t-3 3");
}

</style>
