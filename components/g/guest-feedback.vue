<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7ojoj69o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:guest-feedback" /></template>
<style>
.a7ojoj69o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 2.75h-15q-1.139 0-1.945.805q-.805.806-.805 1.945V15q0 2.75 2.75 2.75h.25v2.75q0 .125.041.243q.04.119.117.217q.045.059.101.107t.12.085q.064.036.135.06q.07.023.143.032t.147.004t.145-.025q.071-.019.137-.053q.066-.033.124-.078l4.297-3.342H19.5q2.75 0 2.75-2.75V5.5q0-2.75-2.75-2.75m-6.304 4.471l.159.396q.171.427.629.469l.512.047q.865.079 1.134.906t-.386 1.401l-.36.314q-.32.28-.244.699l.106.583q.156.862-.576 1.343t-1.461-.005l-.293-.195q-.416-.277-.832 0l-.293.195q-.729.486-1.461.005t-.576-1.343l.106-.583q.076-.419-.244-.699l-.36-.315q-.655-.572-.386-1.4q.269-.827 1.135-.906l.51-.047q.459-.042.63-.468l.159-.397q.325-.809 1.196-.809t1.196.808z");
}

</style>
