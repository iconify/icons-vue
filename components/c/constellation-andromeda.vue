<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8rjuitla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:constellation-andromeda" /></template>
<style>
.c8rjuitla {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.5 5.501v-.002q0-.828.585-1.414q.586-.586 1.415-.586t1.415.586t.585 1.414q.001.829-.585 1.416q-.586.586-1.415.586t-1.415-.586t-.585-1.414m-2.25.999q-2 0-2 2t2 2t2-2t-2-2m-8.5 4q-2 0-2 2t2 2t2-2t-2-2m5.286 1.849l.827-1.363q.519.489 1.351.665l-.827 1.363q-.519-.489-1.351-.665M10 15.5q0-2 2-2t2 2t-2 2t-2-2m-4.059.852l.537-.759q-.806-.227-1.284-.783l-.472.667q.59.238 1.076.725q.074.074.143.15M1.5 18.5q0-.829.586-1.414q.585-.586 1.414-.586t1.414.586q.586.586.586 1.414t-.586 1.414q-.585.586-1.414.586t-1.414-.586T1.5 18.5");
}

</style>
