<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGBG0sQc9u" class="ux_sh-8mz"/></defs><circle class="efqo7obet"/><circle class="u3psqrlzl"/><use href="#SVGBG0sQc9u" class="e0ty9gbgt"/><path class="o3r3gvskn"/><use href="#SVGBG0sQc9u" class="pfsdhbbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:japanese-congratulations-button" /></template>
<style>
.e0ty9gbgt {
  opacity: var(--svg-opacity--0-65, 0.65);
}

.efqo7obet {
  cx: 64px;
  cy: 64px;
  r: 60px;
  fill: var(--svg-color--c33, #c33);
}

.o3r3gvskn {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M35.6 104.5c-2.6 0-4-1.3-4-4v-28c-2.7 2.7-5.1 4.9-7.3 6.6c-1.4 1-2.5 1.4-3.4 1.3s-1.8-1-2.5-2.4c-.6-1.3-.9-2.4-.6-3.3c.2-.9 1-1.8 2.2-2.6c4.2-3 8.2-6.7 11.9-11c3.8-4.4 6.9-9 9.2-13.7H23.4c-2.5 0-3.7-1.2-3.7-3.7s1.2-3.7 3.7-3.7h8.3V28.7c0-2.6 1.3-4 4-4c2.6 0 4 1.3 4 4v11.2h6.1c1.7 0 2.9.5 3.5 1.6s.7 2.6.1 4.5c-1.8 4.8-4.4 9.7-7.8 14.9c2.8 2.5 6.3 5.7 10.5 9.8c.9.8 1.3 1.6 1.1 2.3c-.1.5-.5 1.3-1.4 2.5c-1.1 1.4-2 2.1-2.8 2.2c-1 0-1.9-.7-3-1.9c-1.8-2.2-4-4.6-6.4-7.2v32c0 2.6-1.4 3.9-4 3.9m12.9-2.4q-3-3.75 2.1-6.9c4-3.1 6.9-7.4 8.5-12.8c1.3-4.2 2.1-10.2 2.5-18.1h-4.3c-1.1 0-2-.3-2.7-1s-1-1.6-1-2.7V35.1c0-1.7.5-3.1 1.6-4.1c1.1-1.1 2.4-1.6 4.1-1.6h29.9c1.7 0 3.1.5 4.1 1.6c1.1 1.1 1.6 2.4 1.6 4.1v23.5c0 1.7-.5 3.1-1.6 4.1c-1.1 1.1-2.4 1.6-4.1 1.6h-4.8V94c0 1.3.1 2.2.3 2.6s.7.5 1.5.5h4.6c.5 0 .9-.2 1.2-.7c.3-.4.5-1.3.6-2.6c.1-2.2.5-4 1.1-5.4c.9-1.8 2-2.3 3.4-1.7c.9.4 1.5 1.4 1.8 3.1c.3 1.3.4 2.6.3 4c-.4 3.8-1.2 6.4-2.3 7.9c-1.1 1.4-2.9 2.2-5.4 2.2h-6.8c-3.3 0-5.6-.7-6.7-2.1c-1.1-1.3-1.6-3.9-1.6-7.7V64.3h-7c-.5 9.7-1.7 17.2-3.4 22.4c-2.3 6.7-6.1 11.9-11.5 15.8c-2.5 1.5-4.5 1.4-6-.4m14.8-45.2h21.5q2.1 0 2.1-2.1V38.9q0-2.1-2.1-2.1H63.3q-2.1 0-2.1 2.1v15.9q0 2.1 2.1 2.1");
}

.pfsdhbbki {
  opacity: var(--svg-opacity--0-3, 0.3);
}

.u3psqrlzl {
  cx: 60.1px;
  cy: 63.1px;
  r: 56.1px;
  fill: var(--svg-color--f44336, #f44336);
}

.ux_sh-8mz {
  fill: var(--svg-color--ff8a80, #ff8a80);
  d: path("M24.4 29.7c4.5-7.1 14.1-13 24.1-14.8c2.5-.4 5-.6 7.1.2c1.6.6 2.9 2.1 2 3.8c-.7 1.4-2.6 2-4.1 2.5c-9.4 3.1-17.5 9.2-23 17.4c-2 3-5 11.3-8.7 9.2c-3.9-2.3-3.2-9.5 2.6-18.3");
}

</style>
