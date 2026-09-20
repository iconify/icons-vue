<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGSYx41cnh)" class="e01tcs8om"/><path fill="url(#SVGGdYzpc1O)" class="b6azpw5on"/><defs><linearGradient id="SVGSYx41cnh" x1="2.676" x2="20.968" y1="9.327" y2="9.327" gradientUnits="userSpaceOnUse"><stop class="fn6jy4bmb"/><stop offset="1" class="n_g49pbgd"/></linearGradient><linearGradient id="SVGGdYzpc1O" x1="3.122" x2="22.471" y1="12.45" y2="12.45" gradientUnits="userSpaceOnUse"><stop offset=".67" class="vvhpivatw"/><stop offset=".95" class="ryed-hb8m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ipor" /></template>
<style>
.b6azpw5on {
  d: path("M13.971 12.855c2.682-.09 5.634-.32 7.029-.45c-1.373-.099-4.135-.27-6.629-.356l-.405.81zM12.166 12l-.53.9a83 83 0 0 1-4.55-.175l-.373-.559q2.724-.155 5.453-.166M3 12.405c.518-.04 1.246-.09 2.088-.144l.194.342c-.941-.072-1.737-.144-2.282-.198");
}

.e01tcs8om {
  d: path("M9.975 17.4L3 9.3l6.975 6.75l6.3-8.55l.675.9l1.148-1.8L21 12.45l-2.925-4.725l-1.125 1.8l-.675-.675z");
}

.fn6jy4bmb {
  stop-color: var(--svg-color--e6da88, #e6da88);
}

.ft5dv1b6b {
  fill: none;
}

.n_g49pbgd {
  stop-color: var(--svg-color--e15f50, #e15f50);
}

.ryed-hb8m {
  stop-color: var(--svg-color--2a3985, #2a3985);
}

.vvhpivatw {
  stop-color: var(--svg-color--2e80bf, #2e80bf);
}

</style>
