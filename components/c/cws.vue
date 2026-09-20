<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u1d61uuvb"/><path clip-rule="evenodd" class="kohcf09pv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cws" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kohcf09pv {
  fill: var(--svg-color--d7a049, #d7a049);
  fill-rule: evenodd;
  d: path("M12 21a9 9 0 0 0 9-9a9 9 0 1 0-9 9m0-.474a8.528 8.528 0 0 0 6.029-14.555A8.526 8.526 0 1 0 12 20.526M7.737 15.16c3.946 1.45 7.645.602 9 0v.493c-3.491 1.397-7.456.583-9 0zm3.79-7.422v4.974l.09.123l1.719 2.472v.01c1.217-.048 2.776-.483 3.4-.697v-.421zm3.315 3.42l1.895 2.264v-5.21zm-4.798.194l-1.781 3.283c1.369.54 3.619.73 4.684.682l-2.903-3.96z");
}

.u1d61uuvb {
  fill: var(--svg-color--fcf8f0, #fcf8f0);
  d: path("m10.105 10.731l1.42-2.994l5.211 6.461v.427c-1.074.364-2.19.59-3.32.672zm-2.369 3.657c.152.09.332.17.521.246l1.786-3.283l-2.307-3.14z");
}

</style>
