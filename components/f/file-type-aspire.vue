<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ms7yyzb_i"><path class="x10lg-byo"/><path class="evm3q31ay"/><path class="napfiybdk"/><path class="vwnwaybuv"/><path class="ug4jdib1d"/><path class="wj8o2y8rt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-aspire" /></template>
<style>
.evm3q31ay {
  fill: var(--svg-color--7455dd, #7455dd);
  d: path("M24.122 18.024h-7.26l-.861-1.497l-2.498-4.326a1.24 1.24 0 0 0-.479-.47a1.303 1.303 0 0 0-1.784.479l3.63-6.285A1.3 1.3 0 0 1 16 5.272a1.3 1.3 0 0 1 1.132.653l3.613 6.258l.008.018l.018.026z");
}

.ms7yyzb_i {
  stroke-width: var(--svg-stroke-width--0-109px, 0.109px);
}

.napfiybdk {
  fill: var(--svg-color--9780e5, #9780e5);
  d: path("M28.186 25.423c0 .722-.584 1.305-1.306 1.305h-7.25a1.304 1.304 0 0 0 1.131-1.958l-3.63-6.284l-.27-.462h7.26l3.89 6.746c.114.191.175.418.175.653");
}

.ug4jdib1d {
  fill: var(--svg-color--dcd5f6, #dcd5f6);
  d: path("M13.677 25.423c0 .722-.584 1.305-1.306 1.305h-7.25a1.304 1.304 0 0 1-1.132-1.958l3.516-6.093c.235-.4.67-.653 1.132-.653s.879.244 1.114.627l2.585 4.222l1.149 1.87q.015.014.017.027c.114.192.175.418.175.653");
}

.vwnwaybuv {
  fill: var(--svg-color--b9aaee, #b9aaee);
  d: path("M20.936 25.423c0 .722-.584 1.305-1.306 1.305h-7.26a1.304 1.304 0 0 0 1.132-1.958q-.002-.013-.017-.026l-1.149-1.871l-2.585-4.222a1.31 1.31 0 0 0-1.114-.627h8.225l.27.462l.11.191l3.52 6.093c.104.192.174.418.174.653");
}

.wj8o2y8rt {
  fill: var(--svg-color--9780e5, #9780e5);
  d: path("M16.863 18.024H8.637c-.461 0-.896.252-1.131.653l.374-.653l3.325-5.754l.035-.052v-.008a1.303 1.303 0 0 1 1.784-.48c.209.114.366.28.479.47L16 16.528z");
}

.x10lg-byo {
  fill: var(--svg-color--512bd4, #512bd4);
  d: path("M5.12 28.469a3.05 3.05 0 0 1-2.628-4.588l7.257-12.57l.03-.044l3.582-6.213a3.06 3.06 0 0 1 2.64-1.523c1.084 0 2.095.583 2.638 1.523l10.88 18.845a3.05 3.05 0 0 1-2.639 4.57z");
}

</style>
