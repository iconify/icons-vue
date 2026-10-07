<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ms7yyzb_i"><path class="rmvx6s19s"/><path class="hedn3zbzx"/><path class="htm7grb4r"/><path class="h1ba_acfy"/><path class="m9p8te03h"/><path class="xf6_gdctw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-aspire" /></template>
<style>
.h1ba_acfy {
  fill: var(--svg-color--b9aaee, #b9aaee);
  d: path("M20.936 25.423c0 .722-.583 1.306-1.306 1.306h-7.259a1.304 1.304 0 0 0 1.132-1.959c0-.008-.009-.017-.018-.026l-1.149-1.871l-2.585-4.222a1.31 1.31 0 0 0-1.114-.626h8.226l.27.46l.11.192l3.519 6.093c.104.192.174.418.174.653");
}

.hedn3zbzx {
  fill: var(--svg-color--7455dd, #7455dd);
  d: path("M24.122 18.024h-7.26l-.86-1.497l-2.499-4.326a1.24 1.24 0 0 0-.479-.47a1.303 1.303 0 0 0-1.784.479l3.63-6.285A1.3 1.3 0 0 1 16 5.273c.488 0 .906.26 1.132.652l3.612 6.259l.009.017l.017.026z");
}

.htm7grb4r {
  fill: var(--svg-color--9780e5, #9780e5);
  d: path("M28.186 25.423c0 .722-.583 1.306-1.306 1.306h-7.25a1.304 1.304 0 0 0 1.132-1.959l-3.63-6.284l-.27-.461h7.26l3.89 6.745c.113.192.174.418.174.653");
}

.m9p8te03h {
  fill: var(--svg-color--dcd5f6, #dcd5f6);
  d: path("M13.677 25.423c0 .722-.583 1.306-1.306 1.306h-7.25a1.304 1.304 0 0 1-1.132-1.959l3.517-6.093a1.305 1.305 0 0 1 2.245-.026l2.586 4.222l1.148 1.871q.017.014.018.026c.113.192.174.418.174.653");
}

.ms7yyzb_i {
  stroke-width: var(--svg-stroke-width--0-109px, 0.109px);
}

.rmvx6s19s {
  fill: var(--svg-color--512bd4, #512bd4);
  d: path("M5.12 28.469a3.05 3.05 0 0 1-2.628-4.588l7.258-12.57l.03-.044l3.582-6.212A3.06 3.06 0 0 1 16 3.53c1.084 0 2.095.584 2.638 1.523l10.88 18.845a3.05 3.05 0 0 1-2.639 4.57z");
}

.xf6_gdctw {
  fill: var(--svg-color--9780e5, #9780e5);
  d: path("M16.863 18.024H8.638c-.462 0-.897.252-1.132.653l.374-.653l3.325-5.753l.035-.053v-.008a1.303 1.303 0 0 1 1.784-.479c.21.113.366.279.48.47L16 16.527z");
}

</style>
