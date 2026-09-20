<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGqglUTcaT)" class="j2vggfbmp"/><path fill="url(#SVGbNUTtbeq)" class="s2b5o4b6j"/><defs><linearGradient id="SVGqglUTcaT" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="yr4-n221q"/><stop offset="1" class="d--je6q6f"/></linearGradient><linearGradient id="SVGbNUTtbeq" x1="11.999" x2="11.999" y1="3" y2="19.941" gradientUnits="userSpaceOnUse"><stop class="yydbpey9k"/><stop offset="1" class="n7nnoofai"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kap" /></template>
<style>
.d--je6q6f {
  stop-color: var(--svg-color--d38b3e, #d38b3e);
}

.ft5dv1b6b {
  fill: none;
}

.j2vggfbmp {
  d: path("M7.738 9.353L4.058 21l5.93-3.23l.323.18l-1.075-3.6l-.53 1.626l-.603-.265l.8-2.461zm8.439 0L19.94 21l-6.072-3.23l-.328.18l1.1-3.6l.54 1.626l.62-.265l-.82-2.461l1.201-3.897z");
}

.n7nnoofai {
  stop-color: var(--svg-color--cc7229, #cc7229);
}

.s2b5o4b6j {
  d: path("m11.999 3l-2.647 8.195l2.647 8.746l2.647-8.746zm-1.859 8.211L12 5.441l1.858 5.77L12 17.326z");
}

.yr4-n221q {
  stop-color: var(--svg-color--dba646, #dba646);
}

.yydbpey9k {
  stop-color: var(--svg-color--dcac4a, #dcac4a);
}

</style>
