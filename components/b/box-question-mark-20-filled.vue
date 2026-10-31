<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="yl04_3_yp"/><path class="mlwwgabql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:box-question-mark-20-filled" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mlwwgabql {
  d: path("M17.965 5.622q.035.158.035.324v4.312A5.48 5.48 0 0 0 14.5 9a5.48 5.48 0 0 0-4 1.726V8.608zm-4.935.898L10 7.73L2.58 4.762q.163-.128.363-.209L5.528 3.52zM8.7 2.25a3.5 3.5 0 0 1 2.6 0l5.757 2.303q.2.08.364.21L14.375 5.98l-7.5-3z");
}

.yl04_3_yp {
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m0 6.38a.625.625 0 1 0 0 1.25a.625.625 0 0 0 0-1.25m0-4.876c-1.048 0-1.864.817-1.854 1.954a.5.5 0 1 0 1-.01c-.005-.579.36-.944.854-.944c.472 0 .854.391.854.949c0 .202-.072.315-.36.544l-.278.215c-.506.404-.716.718-.716 1.289a.5.5 0 0 0 .992.09l.01-.157c.018-.147.101-.253.347-.448l.277-.215c.513-.41.728-.732.728-1.318c0-1.104-.823-1.95-1.854-1.95m-5-2.895v3.6a5.49 5.49 0 0 0 0 4.583v.712a3.5 3.5 0 0 1-.8-.215l-5.757-2.303A1.5 1.5 0 0 1 2 13.593V5.945q0-.166.035-.324z");
}

</style>
