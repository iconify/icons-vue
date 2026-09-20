<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="yfqz3ccoh"/><path class="h0_xb_buo"/><path class="zl_s4rhha"/><path class="lyz303zaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:file-cabinet" /></template>
<style>
.h0_xb_buo {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M28 16a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1zm0 17a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V20a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1z");
}

.lyz303zaw {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M15 5h6v3h-6zm0 17h6v3h-6zm9-8.97a.97.97 0 0 1-.97.97H12.97a.97.97 0 0 1-.97-.97v-.06a.97.97 0 0 1 .97-.97h10.06a.97.97 0 0 1 .97.97zm0 16.999a.97.97 0 0 1-.97.971H12.97a.97.97 0 0 1-.97-.971v-.059a.97.97 0 0 1 .97-.97h10.06c.535 0 .97.435.97.971z");
}

.yfqz3ccoh {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M30 34a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2V2a2 2 0 0 1 2-2h20a2 2 0 0 1 2 2z");
}

.zl_s4rhha {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M22 8a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1zm0 17a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1z");
}

</style>
