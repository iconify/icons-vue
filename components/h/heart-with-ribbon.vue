<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="sanifumun"/><path class="poxk5v_rz"/><path class="lypj3-bxf"/><path class="lyjuxe14y"/><circle class="mz_y_i68z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:heart-with-ribbon" /></template>
<style>
.lyjuxe14y {
  fill: var(--svg-color--fdcb58, #fdcb58);
  d: path("m16.802 9.194l-7.879 5.515l-7.878-5.515C.47 8.792 0 9.036 0 9.738v14.658c0 .703.48.965 1.069.582l7.854-5.106l7.854 5.106c.588.383 1.069.121 1.069-.582V9.738c.001-.702-.47-.946-1.044-.544");
}

.lypj3-bxf {
  fill: var(--svg-color--fdd888, #fdd888);
  d: path("M14 18v18l-5-5l-5 5V18z");
}

.mz_y_i68z {
  cx: 9px;
  cy: 17px;
  r: 4px;
  fill: var(--svg-color--fdd888, #fdd888);
}

.poxk5v_rz {
  fill: var(--svg-color--fdd888, #fdd888);
  d: path("M36 15c-1 5-4 8-4 8H4s-3-3-4-8z");
}

.sanifumun {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M35.885 11.833c0-5.45-4.418-9.868-9.867-9.868c-3.308 0-6.227 1.633-8.018 4.129c-1.791-2.496-4.71-4.129-8.017-4.129c-5.45 0-9.868 4.417-9.868 9.868c0 .772.098 1.52.266 2.241C1.751 22.587 11.216 31.568 18 34.034c6.783-2.466 16.249-11.447 17.617-19.959c.17-.721.268-1.469.268-2.242");
}

</style>
