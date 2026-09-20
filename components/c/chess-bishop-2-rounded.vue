<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4eh8pb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chess-bishop-2-rounded" /></template>
<style>
.u4eh8pb-s {
  fill: currentColor;
  d: path("M6.616 17.289q-.737-.91-1.176-2.46Q5 13.279 5 11.636Q5 9.672 6.48 7.89t4.495-3.47q-.183-.181-.29-.438q-.108-.257-.108-.54q0-.594.414-1.018Q11.406 2 12 2t1.009.424t.414 1.018q0 .296-.108.538q-.107.241-.304.422q3.01 1.477 4.5 3.266Q19 9.458 19 11.618q0 1.713-.434 3.274q-.433 1.562-1.162 2.397zM5.962 21q-.414 0-.688-.284Q5 20.433 5 20.02t.284-.687t.697-.274h12.058q.413 0 .687.274t.274.687t-.274.697t-.687.284zm5.538-9v1.404q0 .213.143.357t.357.143t.357-.143t.143-.357V12h1.346q.213 0 .357-.143q.143-.143.143-.357t-.143-.357t-.357-.143H12.5V9.616q0-.214-.143-.357T12 9.116t-.357.143t-.143.357V11h-1.365q-.214 0-.357.143q-.144.143-.144.357t.144.357t.356.143z");
}

</style>
