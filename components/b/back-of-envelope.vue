<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="yzxf_pheg"/><path class="tb53qs4ka"/><path class="cog80fb7d"/><path class="rxhfm_5cl"/><path class="iixoxqb8s"/><path class="mace6q20w"/><circle class="rix7ib3ha"/><circle class="kzj-1xbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:back-of-envelope" /></template>
<style>
.cog80fb7d {
  fill: var(--svg-color--e7e6e6, #e7e6e6);
  d: path("M.127 55.688L32.06 23.68L64 55.688z");
}

.iixoxqb8s {
  fill: var(--svg-color--e7e6e6, #e7e6e6);
  d: path("M63.873 7.688L31.938 39.696L0 7.688z");
}

.kzj-1xbgo {
  cx: 32.14px;
  cy: 33.965px;
  r: 6.917px;
  fill: var(--svg-color--dd4e66, #dd4e66);
}

.mace6q20w {
  fill: var(--svg-color--c13a51, #c13a51);
  d: path("M33.02 42.718c.051.023.1.061.152.08c1.678.633 3.615 1.066 5.098-.27c1.072-.965 1.494-2.283 1.369-3.639c2.076-1 4.088-2.877 2.9-5.396c-.484-1.029-1.266-1.654-2.176-2.037c.113-.34.207-.68.215-1.051c.043-1.854-1.049-3.199-2.664-3.369c-.764-.951-1.709-1.748-2.834-2.289c-1.525-.736-3.518-.211-4.697 1.012c-.037-.082-.051-.168-.094-.248c-1.461-2.691-5.488-2.408-6.092.777c-.256 1.354.178 2.686.902 3.826c-.139.539-.201 1.105-.256 1.591c.18-1.599-2.148.807-2.633 1.414c-1.699 2.128-1.203 5.534 1.414 6.679c.395.156.805.25 1.229.273c.242.029.43.049.578.059c.184.877.482 1.662 1.184 2.404c1.623 1.721 4.521 2.592 6.254.455c.067-.08.091-.185.151-.271");
}

.rix7ib3ha {
  cx: 32.14px;
  cy: 33.965px;
  r: 8.07px;
  fill: var(--svg-color--ce3a4c, #ce3a4c);
}

.rxhfm_5cl {
  fill: var(--svg-color--bcbec0, #bcbec0);
  d: path("M64 7.688L31.938 44.25L0 7.688z");
}

.tb53qs4ka {
  fill: var(--svg-color--bcbec0, #bcbec0);
  d: path("M0 55.688L32.06 20.94L64 55.688z");
}

.yzxf_pheg {
  fill: var(--svg-color--f1f2f2, #f1f2f2);
  d: path("M0 7.688h64v48H0z");
}

</style>
