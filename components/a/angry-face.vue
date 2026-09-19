<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="ac3iyz33e"/><path class="dxi7azbfl"/><path class="tb_4qwcww"/><path class="r5w6ajevw"/><path class="zujiscuvg"/><ellipse class="dmwk6lr8m"/><path class="d5sxbmrji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:angry-face" /></template>
<style>
.ac3iyz33e {
  cx: 31.73px;
  cy: 31.73px;
  r: 31.73px;
  fill: var(--svg-color--fbbf67, #fbbf67);
}

.d5sxbmrji {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M28.816 26.917c-1.868-6.641-10.356-10.152-16.683-10.223c-1.848-.021-2.269 2.863-.394 2.882c5.326.061 12.756 2.234 14.359 7.934c.51 1.808 3.222 1.195 2.718-.593M21.26 51.3c-.625.713-.239 1.904.79 1.904c1.188 0 5.451-1.799 9.68-1.799c4.734 0 9.421 1.799 9.68 1.799c1.028 0 1.406-1.191.795-1.904c-5.673-6.541-15.282-6.541-20.945 0");
}

.dmwk6lr8m {
  cx: 20.706px;
  cy: 31.02px;
  fill: var(--svg-color--25333a, #25333a);
  rx: 4.172px;
  ry: 5.06px;
}

.dxi7azbfl {
  fill: var(--svg-color--fff, #fff);
  d: path("M35.823 31.352c0 5.336 2.887 9.656 6.449 9.656s6.448-4.32 6.448-9.656c0-5.333-2.887-9.656-6.448-9.656s-6.449 4.322-6.449 9.656");
}

.r5w6ajevw {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M34.16 27.25c1.867-6.641 10.355-10.152 16.683-10.223c1.848-.021 2.27 2.863.394 2.882c-5.325.061-12.756 2.234-14.358 7.934c-.511 1.807-3.223 1.194-2.719-.593");
}

.tb_4qwcww {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M38.1 31.352c0 2.795 1.865 5.06 4.172 5.06s4.171-2.265 4.171-5.06s-1.865-5.059-4.171-5.059s-4.172 2.265-4.172 5.059");
}

.zujiscuvg {
  fill: var(--svg-color--fff, #fff);
  d: path("M27.16 31.02c0 5.336-2.887 9.656-6.449 9.656s-6.449-4.32-6.449-9.656c0-5.333 2.886-9.656 6.449-9.656s6.449 4.323 6.449 9.656");
}

</style>
