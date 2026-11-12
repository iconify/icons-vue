<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m1-2fe5aj"/><path class="wvwp3s2zt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:firewall-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m1-2fe5aj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.5 7.5c0-.317-.068-.455-.219-.725a8 8 0 0 1-.175-.328c-.355-.71-.455-1.482-.217-2.245c.253-.808.837-1.463 1.486-1.983a1.002 1.002 0 0 1 1.606.585c.199.997.818 1.795 1.619 2.396a1 1 0 0 1 .107.093C15.71 6.296 16 7.626 16 9a4 4 0 0 1-.315 1.557A3.998 3.998 0 0 1 8 9c0-.79.22-1.634.793-2.207A1 1 0 0 1 10.5 7.5");
}

.wvwp3s2zt {
  d: path("M10.5 7.5c0-.128-.009-.261-.05-.383c-.04-.12-.108-.233-.169-.342a8 8 0 0 1-.175-.328c-.836-1.671-.087-3.143 1.269-4.228a1 1 0 0 1 1.25 1.562c-.328.262-.697.603-.827 1.017c-.114.367.056.691.229 1.002c.122.218.239.442.319.679c.186.555.228 1.252-.004 1.8a2.003 2.003 0 0 1-2.948.888A2 2 0 0 1 8.5 7.5a1 1 0 0 1 2 0M5 14h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3m3 2H5a.997.997 0 0 0-1 1h4Zm2 1h10a1 1 0 0 0-1-1h-9Zm-1 2H4a1 1 0 0 0 1 1h9v-1Zm7 0v1h3a1 1 0 0 0 1-1Z");
}

</style>
