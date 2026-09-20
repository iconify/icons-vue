<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdczeo5df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:blur-medium-rounded" /></template>
<style>
.mdczeo5df {
  fill: currentColor;
  d: path("M8 16.5q-.213 0-.356-.144t-.144-.357t.144-.356T8 15.5h4.442q-.734-.54-1.187-1.312q-.453-.773-.54-1.688H5.463q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143h5.254q.105-.915.549-1.687T12.442 8.5H5q-.213 0-.356-.144T4.5 7.999t.144-.356T5 7.5h10.192q1.868 0 3.184 1.316q1.316 1.315 1.316 3.181t-1.316 3.185t-3.184 1.318zm9.673-2.021q1.02-1.022 1.02-2.481T17.67 9.519T15.19 8.5t-2.478 1.022t-1.02 2.48t1.022 2.479t2.48 1.019t2.479-1.022M4.808 16.5q-.213 0-.356-.144t-.144-.357t.144-.356t.356-.143h.423q.212 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
