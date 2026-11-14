<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mszgfib8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:exclusive-offer" /></template>
<style>
.mszgfib8e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.186 3.459l.166.335q.175.355.565.412l.368.053q.816.118 1.071.901q.254.783-.335 1.357l-.27.261q-.281.274-.214.663l.063.368q.04.234.013.441h4.637q1.036 0 1.768.732t.732 1.768v.5q0 1.036-.732 1.768q-.35.349-.768.532v5.95q0 2.75-2.75 2.75h-11q-2.75 0-2.75-2.75v-5.877q-1.5-.437-1.5-2.373v-.5q0-2.5 2.5-2.5h4.637q-.027-.206.013-.44l.063-.369q.067-.389-.216-.664l-.266-.259q-.591-.575-.337-1.358q.255-.783 1.069-.901l.372-.053q.388-.057.562-.411l.167-.336q.366-.735 1.186-.735t1.186.734zM11.25 20.75v-7h-6v5.75q0 1.25 1.25 1.25zm6.25 0q1.25 0 1.25-1.25v-5.75h-6v7z");
}

</style>
