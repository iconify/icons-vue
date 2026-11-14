<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_0_k1bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:audience-score" /></template>
<style>
.n_0_k1bwk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.75Q3.25 2.75 3.25 6v8q0 3.122 3 3.245V20q0 .136.048.264q.048.127.138.23q.098.112.232.178q.133.066.282.076t.29-.038q.142-.047.254-.146l3.788-3.314H17.5q3.25 0 3.25-3.25V6q0-3.25-3.25-3.25zm6.686 4.709l.166.335q.175.355.565.412l.368.053q.816.118 1.071.901q.254.783-.335 1.357l-.27.261q-.281.274-.214.663l.063.368q.138.811-.526 1.294q-.665.484-1.393.102l-.332-.174q-.349-.184-.698 0l-.331.174q-.729.382-1.394-.102q-.664-.483-.526-1.293l.063-.369q.067-.389-.216-.664l-.266-.259q-.591-.575-.337-1.358q.255-.783 1.069-.901l.372-.053q.388-.057.562-.411l.167-.336q.366-.735 1.186-.735t1.186.734z");
}

</style>
