<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yxr76rtxn"/><path class="qk_lrz35t"/><path class="be4kutl6f"/><path class="ze22m6-9f"/><path class="osyfxspln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-aseprite" /></template>
<style>
.be4kutl6f {
  fill: var(--svg-color--7d929e, #7d929e);
  d: path("M6.67 3.87h18.66v24.26H6.67M4.8 5.73h22.4v20.54H4.8z");
}

.osyfxspln {
  fill: var(--svg-color--655561, #655561);
  d: path("M10.4 9.47h1.87v7.46H10.4zm9.33 0h1.87v7.46h-1.87z");
}

.qk_lrz35t {
  fill: var(--svg-color--655561, #655561);
  d: path("M6.67 2h18.66v28H6.67M4.8 3.87h22.4v24.26H4.8M2.93 5.73h26.14v20.54H2.93");
}

.yxr76rtxn {
  fill: var(--svg-color--6d6a76, #6d6a76);
  d: path("M4.8 2h22.4v28H4.8M2.93 3.87h26.14v24.26H2.93");
}

.ze22m6-9f {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.67 3.87h18.66V24.4H6.67M4.8 5.73h22.4v16.8H4.8z");
}

</style>
