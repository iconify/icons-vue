<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGxA0I8bQs)" class="fh3r4lbwv"/><path class="odf0hhb7s"/><path class="y112hnz-t"/><defs><linearGradient id="SVGxA0I8bQs" x1="12" x2="12" y1="4.421" y2="19.578" gradientUnits="userSpaceOnUse"><stop class="ol22nz9oj"/><stop offset=".19" class="z4bpv4b7p"/><stop offset=".49" class="ym0g8rbdw"/><stop offset=".72" class="dch-labwu"/><stop offset="1" class="kgvyejbhb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gdcc" /></template>
<style>
.dch-labwu {
  stop-color: var(--svg-color--e21d91, #e21d91);
}

.fh3r4lbwv {
  d: path("M11.052 14.368c-.336 1.753-1.586 4.737-3.789 4.737c-2.368 0-3.316-4.955-3.316-7.105c0-3.79 1.658-7.105 3.316-7.105c1.79 0 3.415 2.69 3.79 4.263c-.635-2.776-2-4.737-3.79-4.737C4.909 4.42 3 7.812 3 12s1.909 7.578 4.263 7.578c1.89 0 3.23-2.183 3.79-5.21");
}

.ft5dv1b6b {
  fill: none;
}

.kgvyejbhb {
  stop-color: var(--svg-color--ad2b88, #ad2b88);
}

.odf0hhb7s {
  fill: var(--svg-color--eceded, #eceded);
  d: path("M9.759 14.368c-.35 1.54-1.023 3.079-2.07 3.079c-1.199 0-2.07-1.165-2.78-2.113l-.015-.019c.587 1.705 1.62 2.842 2.795 2.842c1.378 0 2.558-1.563 3.06-3.79h-.995zm.871-5.21c-.554-1.971-1.662-3.316-2.941-3.316c-1.28 0-2.24 1.345-2.795 3.316l.18-.299c.654-1.113 1.36-2.307 2.615-2.307c1.023 0 1.648 1.241 1.999 2.606h.947z");
}

.ol22nz9oj {
  stop-color: var(--svg-color--6602ff, #6602ff);
}

.y112hnz-t {
  fill: var(--svg-color--ce1db4, #ce1db4);
  d: path("M7.264 10.578h2.368v-.947H7.264c-.758 0-.948.63-.948.947v2.369c0 .757.63.947.947.947h1.422c.757 0 .947-.63.947-.947v-1.421H7.737v.947h.948v.474H7.263zm7.578 2.369v-2.369h1.421v.474h.948v-.474c0-.473-.251-.947-.948-.947h-1.42c-.759 0-.948.63-.948.947v2.369c0 .757.63.947.947.947h1.421c.758 0 .948-.63.948-.947v-.474h-.948v.474zm3.79 0v-2.369h1.42v.474H21v-.474c0-.473-.251-.947-.947-.947h-1.421c-.758 0-.948.63-.948.947v2.369c0 .757.63.947.948.947h1.42c.759 0 .948-.63.948-.947v-.474h-.947v.474zm-8.527-2.369v-.947h2.369c.758 0 .947.63.947.947v2.369c0 .757-.63.947-.947.947h-2.369v-2.842h.948v1.895h1.421v-2.369z");
}

.ym0g8rbdw {
  stop-color: var(--svg-color--e74d47, #e74d47);
}

.z4bpv4b7p {
  stop-color: var(--svg-color--9c2597, #9c2597);
}

</style>
