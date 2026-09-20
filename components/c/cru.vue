<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wr3vo0tdi"/><path class="axwvhr2xx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cru" /></template>
<style>
.axwvhr2xx {
  fill: var(--svg-color--f98a16, #f98a16);
  d: path("M12.77 3.113c.27-.15.61-.15.88 0l4.61 2.56c.02.02.05.035.09.06c.87.495.7.855.435 1.1a38 38 0 0 0-1.5 1.575l-.35.375c-.22.235-.54.16-.825.02l-.3-.17l-.24-.14v.005l-1.92-1.07a.92.92 0 0 0-.88 0c-2.62 1.455-5.15 2.95-7.77 4.42v-3.93c0-.3.17-.585.44-.735l7.33-4.075z");
}

.ft5dv1b6b {
  fill: none;
}

.wr3vo0tdi {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.495 18.187l-4.845 2.7c-.27.15-.61.15-.88 0l-7.33-4.08a.85.85 0 0 1-.44-.735v-3.375l4-2.2v3.4c0 .3.15.585.425.735l3.345 1.93c.27.15.61.15.88 0l2.07-1.15c.525-.225.96-.165 1.24.01l.76.74l.866.835c.45.435.26.93-.09 1.19");
}

</style>
