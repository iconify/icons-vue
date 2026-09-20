<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="h6qdigdaz"/><path class="x7nx8zb-g"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:blx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h6qdigdaz {
  fill: var(--svg-color--0094d9, #0094d9);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.x7nx8zb-g {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.73 5.129L12 4l-1.73 1.129v2.093l1.297.916v.865l-3.027 1.6v3.676l-.458.342l-.463-3.296l-.458 3.624l.514.476v1.103l-1.08.661l-1.082-.661v-1.051l.744-.346l.23 1.098l.324-1.44V9.522l2.901-1.7l-.48-.778l-3.286 1.964v5.215l-1.298.687v2.15l1.946 1.21l1.946-1.21v-1.64l.735-.367L12 16.64l2.754-1.6l.571.342l-1.487 1.98l2.054-1.254v-.389l1.6-.908l.994.627v1.111l-.817.588l-.705-.45l.203-.964l-.778.506l-4.16 2.668l-2.5-1.57l-.51.766L12.23 20l4.108-2.638l1.285.908l1.73-1.232v-2.089l-1.817-1.21l-1.626.925l-.45-.42v-3.64l-3.027-1.6v-.68L15.9 9.522l-3.213-2.088l-.229.216l-1.323-.921V5.613L12 5.124l.865.489v.982h-.407l.407.432l4.324 2.495v3.84l.865-.229V9.008L13.73 6.49V5.124zm-4.325 6.196L12 9.795l2.594 1.34v2.92L12 15.575l-2.595-1.522zm1.298.416L12 11.066l1.297.675l-1.297.678zm0 1.66v-1.193l1.08.713v1.194zm2.594-1.193V13.4l-1.08.714V12.92z");
}

</style>
