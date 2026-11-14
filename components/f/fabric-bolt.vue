<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa93oc6in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fabric-bolt" /></template>
<style>
.fa93oc6in {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 7.5q0-2.091 1.005-3.598Q4.356 2.25 6 2.25h12.5q1.644 0 2.745 1.652Q22.25 5.409 22.25 7.5t-1.005 3.598q-.866 1.3-2.069 1.577l-.931 7.913q-.008.067-.028.133q-.02.065-.052.126q-.032.06-.074.114t-.093.099t-.109.081t-.122.06t-.131.037q-.068.012-.136.012h-13q-.066 0-.13-.011q-.073-.013-.142-.04t-.131-.067q-.062-.039-.116-.09q-.053-.051-.095-.112q-.043-.06-.073-.128t-.045-.14t-.018-.146q-.001-.074.011-.146l1.368-7.747q-1.079-.332-1.874-1.525Q2.25 9.591 2.25 7.5m18.5 0q0-3.75-2.25-3.75H8.64q.053.074.105.152Q9.75 5.409 9.75 7.5t-1.005 3.598q-.052.078-.105.152h9.86q2.25 0 2.25-3.75m-3.917 12.25l.824-7H6.629l-1.235 7z");
}

</style>
