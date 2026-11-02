<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nla0t_bxs"/><path class="t3zp3emsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nla0t_bxs {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 7c0-.676.276-1.302.708-1.814c2.465-2.913 10.119-2.913 12.584 0C18.724 5.698 19 6.324 19 7v10c0 .676-.276 1.302-.708 1.814c-2.465 2.913-10.119 2.913-12.584 0C5.276 18.302 5 17.676 5 17Z");
}

.t3zp3emsg {
  d: path("M7.235 7.522c.26.307.613.527.969.705c2.068 1.033 5.524 1.033 7.592 0c.356-.178.709-.398.969-.705c.123-.146.235-.325.235-.522a1 1 0 0 1 2 0c-.001 1.417-1.134 2.428-2.31 3.016c-1.422.711-3.112.984-4.69.984s-3.268-.273-4.69-.984c-.599-.3-1.167-.688-1.602-1.202C5.276 8.302 5 7.676 5 7a1 1 0 0 1 2 0c0 .197.112.376.235.522M5 12a1 1 0 0 1 2 0c0 .197.112.376.235.522c.26.307.613.527.969.705C9.34 13.794 10.743 14 12 14s2.66-.206 3.796-.773c.356-.178.709-.398.969-.705c.123-.146.235-.325.235-.522a1 1 0 0 1 2 0c0 .676-.276 1.302-.708 1.814c-2.465 2.913-10.119 2.913-12.584 0C5.276 13.302 5 12.676 5 12");
}

</style>
