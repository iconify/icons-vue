<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG1MdlAeAz)" clip-rule="evenodd" class="nmomviboi"/><defs><linearGradient id="SVG1MdlAeAz" x1="18.882" x2="4.324" y1="5.382" y2="18.088" gradientUnits="userSpaceOnUse"><stop class="ivd2od8is"/><stop offset=".53" class="plhwb9o2l"/><stop offset="1" class="kxf3fjb5u"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hbb" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ivd2od8is {
  stop-color: var(--svg-color--36c9ff, #36c9ff);
}

.kxf3fjb5u {
  stop-color: var(--svg-color--da26ff, #da26ff);
}

.nmomviboi {
  fill-rule: evenodd;
  d: path("M8.294 9.088H6.176v1.588h2.118zm-2.647 0v1.588H3.53V9.088zM3.53 12.794v-1.588h2.118v1.588zm0 .53v1.588h2.118v-1.589zm2.118 4.219a2.38 2.38 0 0 1-2.102-2.102h2.102zm.53 0V15.44h2.101a2.38 2.38 0 0 1-2.102 2.102m2.117-4.22v1.589H6.176v-1.589zm0-.529v-1.588H6.176v1.588zM6.176 8.559V6.457a2.38 2.38 0 0 1 2.102 2.102zm-.529 0H3.545a2.38 2.38 0 0 1 2.102-2.102zM3 8.823a2.91 2.91 0 0 1 2.647-2.9v-.011h.53v.01a2.913 2.913 0 0 1 2.647 2.901v6.353a2.912 2.912 0 1 1-5.824 0zm17.47.265h-2.117v1.588h2.117zm-2.646 0v1.588h-2.118V9.088zm-2.118 3.706v-1.588h2.117v1.588zm0 .53v1.588h2.117v-1.589zm2.117 4.219a2.38 2.38 0 0 1-2.101-2.102h2.101zm.53 0V15.44h2.102a2.38 2.38 0 0 1-2.102 2.102m2.117-4.22v1.589h-2.117v-1.589zm0-.529v-1.588h-2.117v1.588zm-2.117-4.235V6.457a2.38 2.38 0 0 1 2.102 2.102zm-.53 0h-2.101a2.38 2.38 0 0 1 2.101-2.102zm-2.646.264a2.91 2.91 0 0 1 2.646-2.9v-.011h.53v.01A2.913 2.913 0 0 1 21 8.823v6.353a2.912 2.912 0 1 1-5.823 0zm-5.295.794h1.588v1.589H9.883zm4.236 0H12.53v1.589h1.588zm-1.588 2.648h1.588v1.588H12.53zm-1.06 0H9.883v1.588h1.588z");
}

.plhwb9o2l {
  stop-color: var(--svg-color--7d81ff, #7d81ff);
}

</style>
