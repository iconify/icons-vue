<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4co1mbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:glucometer" /></template>
<style>
.d4co1mbub {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.086 2.031q.457.572 1.363 1.67q4.496 5.448 4.782 8.628q-1.35.249-2.376 1.276q-1.355 1.354-1.355 3.27v1.92q-1.368.705-3 .705q-2.748 0-4.749-2.001T2.75 12.75q0-3.232 4.801-9.049q.906-1.098 1.363-1.67q.094-.116.224-.188q.131-.072.279-.088q.148-.017.292.025q.143.041.26.134q.065.052.117.117M18.875 13.5h-1.75q-3.375 0-3.375 3.375v2.25q0 3.375 3.375 3.375h1.75q3.375 0 3.375-3.375v-2.25q0-3.375-3.375-3.375m-3.625 3.375Q15.25 15 17.125 15h.125q-2 0-2 2zm5.5.125v2.125Q20.75 21 18.875 21h-1.75q-1.875 0-1.875-1.875V17q0 2 2 2h1.5q2 0 2-2m0 0q0-2-2-2h.125q1.875 0 1.875 1.875zm-3.5-.5h1.5q.5 0 .5.5t-.5.5h-1.5q-.5 0-.5-.5t.5-.5");
}

</style>
