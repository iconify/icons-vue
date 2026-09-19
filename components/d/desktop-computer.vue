<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lk2jxsf6q"/><path class="nslfcp0sa"/><path class="he9-25bzu"/><path class="x4z59owsd"/><g class="z3p269btt"><circle class="x31dz8b_s"/><path class="haf3u9d0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:desktop-computer" /></template>
<style>
.haf3u9d0x {
  d: path("M16 58h32v4H16z");
}

.he9-25bzu {
  fill: var(--svg-color--bfbebe, #bfbebe);
  d: path("M24 54c0 4-4 4-8 4h32c-4 0-8 0-8-4v-2H24z");
}

.lk2jxsf6q {
  fill: var(--svg-color--212528, #212528);
  d: path("M62 6c0-2-2-4-4-4H6C4 2 2 4 2 6v38h60z");
}

.nslfcp0sa {
  fill: var(--svg-color--ddd, #ddd);
  d: path("M2 44v4c0 2 2 4 4 4h52c2 0 4-2 4-4v-4z");
}

.x31dz8b_s {
  cx: 32px;
  cy: 47.9px;
  r: 1px;
}

.x4z59owsd {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M6 6h52v34H6z");
}

.z3p269btt {
  fill: var(--svg-color--94989b, #94989b);
}

</style>
