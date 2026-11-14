<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0s33abms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kid-shy" /></template>
<style>
.t0s33abms {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.5 1.75H18q1.76 0 3.005 1.245T22.25 6v12q0 1.76-1.245 3.005T18 22.25h-2.5q-1.76 0-3.005-1.245q-.625-.625-.936-1.38q-3.326.662-6.112-1.462Q2.396 15.837 2.396 12t3.051-6.163q2.786-2.124 6.112-1.462q.311-.755.936-1.38Q13.74 1.75 15.5 1.75m-4.248 4.094Q8.589 5.328 6.357 7.03Q3.896 8.906 3.896 12t2.461 4.97q2.232 1.702 4.895 1.186L11.25 18V6zM8.51 10.25H8.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T7.75 11t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T9.26 11t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
