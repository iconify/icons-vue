<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir0rw51ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:loyalty-progress" /></template>
<style>
.ir0rw51ux {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m18.936 9.209l.166.335q.175.355.565.412l.368.053q.816.118 1.071.901q.254.783-.335 1.357l-.27.261q-.281.274-.214.663l.063.368q.138.811-.526 1.294q-.665.484-1.393.102l-.332-.174q-.349-.184-.698 0l-.331.174q-.729.382-1.394-.102q-.664-.483-.526-1.293l.063-.369q.067-.389-.216-.664l-.266-.259q-.139-.135-.231-.282V12q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.588Q12.831 14 11.25 14q-1.5 0-1.875-1.125Q9 14 7.5 14t-1.875-1.125Q5.25 14 3.75 14q-2 0-2-2t2-2q1.5 0 1.875 1.125Q6 10 7.5 10t1.875 1.125Q9.75 10 11.25 10q1.581 0 1.912 1.25h.588q.168 0 .32.072q.152.071.259.201q-.04-.289.065-.613q.255-.783 1.069-.901l.372-.053q.388-.057.562-.411l.167-.336q.366-.735 1.186-.735t1.186.734z");
}

</style>
