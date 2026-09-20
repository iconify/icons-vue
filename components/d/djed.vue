<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGsE1BScsI)" clip-rule="evenodd" class="qhfs4fbqn"/><path fill="url(#SVG3yBVze8n)" clip-rule="evenodd" class="cqm3lxbkr"/><defs><linearGradient id="SVGsE1BScsI" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="e1muyvbdp"/><stop offset="1" class="qvkdknbsd"/></linearGradient><linearGradient id="SVG3yBVze8n" x1="8.558" x2="13.853" y1="5.382" y2="19.676" gradientUnits="userSpaceOnUse"><stop class="s-2cwdpdy"/><stop offset="1" class="i1pycg06o"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:djed" /></template>
<style>
.cqm3lxbkr {
  fill-rule: evenodd;
  d: path("M12 20.47a8.47 8.47 0 1 0 0-16.94a8.47 8.47 0 0 0 0 16.94M9.183 6.706a.365.365 0 0 0-.36.37c0 .201.159.37.36.37h.223l.312.848h4.595l.297-.847h.2a.35.35 0 0 0 .26-.106a.37.37 0 0 0 .106-.265a.38.38 0 0 0-.106-.265a.36.36 0 0 0-.264-.105zm0 2.117a.365.365 0 0 0-.36.37c0 .202.159.371.36.371h.223l.312.847h4.595l.297-.847h.2a.35.35 0 0 0 .25-.11a.37.37 0 0 0 .105-.266a.38.38 0 0 0-.105-.259a.36.36 0 0 0-.25-.106H9.179zm0 2.118a.366.366 0 0 0-.36.37c0 .202.159.371.36.371h.223l.476.847h4.235l.493-.847h.2a.35.35 0 0 0 .26-.106a.37.37 0 0 0 .106-.265a.38.38 0 0 0-.106-.264a.36.36 0 0 0-.264-.106zm4.934 1.853H9.882v.794h4.235zM9.183 17.61a.365.365 0 0 0-.36.371c0 .207.159.37.355.37h5.633a.35.35 0 0 0 .26-.105a.37.37 0 0 0 .105-.265a.38.38 0 0 0-.106-.265a.36.36 0 0 0-.264-.106h-.17c-.222-.227-.519-.953-.519-2.446v-1.048H12.53v3.706h-1.06v-3.706H9.882v1.048c0 1.493-.291 2.219-.514 2.452h-.19z");
}

.e1muyvbdp {
  stop-color: var(--svg-color--debf54, #debf54);
}

.ft5dv1b6b {
  fill: none;
}

.i1pycg06o {
  stop-color: var(--svg-color--c79536, #c79536);
}

.qhfs4fbqn {
  fill-rule: evenodd;
  d: path("M12 20.47a8.47 8.47 0 1 0 0-16.94a8.47 8.47 0 0 0 0 16.94m0 .53a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.qvkdknbsd {
  stop-color: var(--svg-color--aa7d2b, #aa7d2b);
}

.s-2cwdpdy {
  stop-color: var(--svg-color--faca56, #faca56);
}

</style>
