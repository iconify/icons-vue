<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dv_7isbta"/><path class="tpzfzi76a"/><path class="gn-xblqbd"/><path class="m_4-mibtx"/><path class="v9rm-h89j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-cspell" /></template>
<style>
.dv_7isbta {
  fill: var(--svg-color--b4301c, #b4301c);
  d: path("M2 20.87h28V27a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.gn-xblqbd {
  d: path("M10.7 2h2.18v28H10.7Z");
}

.m_4-mibtx {
  fill: var(--svg-color--f6f200, #f6f200);
  d: path("M12.88 2H27a3 3 0 0 1 3 3v14H12.88Z");
}

.tpzfzi76a {
  d: path("M2 18.94h28v2H2Z");
}

.v9rm-h89j {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M5 2h5.67v17H2V5a3 3 0 0 1 3-3");
}

</style>
