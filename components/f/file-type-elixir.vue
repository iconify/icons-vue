<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGSwnCKblo" x1="17.249" x2="14.973" y1="-335.597" y2="-309.994" gradientTransform="matrix(1 0 0 -1 0 -306)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".01" class="katb62atz"/><stop offset=".09" class="ss-3arbcm"/><stop offset=".2" class="tlofp4x_d"/><stop offset=".32" class="q-pyj5bzu"/><stop offset=".5" class="k3yvk7vas"/><stop offset="1" class="jr1ql-bvn"/></linearGradient></defs><path class="t3pao9bbb"/><path class="qy5e9vere"/><path fill="url(#SVGSwnCKblo)" class="mnn-osbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-elixir" /></template>
<style>
.jr1ql-bvn {
  stop-color: var(--svg-color--26003d, #26003d);
}

.k3yvk7vas {
  stop-color: var(--svg-color--2d0843, #2d0843);
  stop-opacity: 0.97;
}

.katb62atz {
  stop-color: var(--svg-color--f7f6f8, #f7f6f8);
  stop-opacity: 0.04;
}

.mnn-osbuw {
  d: path("M17.385 9.921C20.369 14 24.319 13.7 25 19.641c.094 6.923-3.6 9.283-6.237 9.948c-4.5 1.279-8.514-.645-10.094-5c-3.035-7 2.651-18.514 6.31-20.915a15.1 15.1 0 0 0 2.37 6.237Z");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.q-pyj5bzu {
  stop-color: var(--svg-color--452459, #452459);
  stop-opacity: 0.86;
}

.qy5e9vere {
  fill: var(--svg-color--26003d, #26003d);
  d: path("M18.248 10.618c4.47 4.823 6.445 4.979 6.237 10.478c-.249 6.476-4.543 8.191-7.058 8.42c-4.2.551-7.495-1.528-8.358-5.686c-1.757-6.767 3.909-17.807 7.568-19.47a15.3 15.3 0 0 0 1.621 6.24Z");
  opacity: var(--svg-opacity--0-25, 0.25);
}

.ss-3arbcm {
  stop-color: var(--svg-color--aa9cb3, #aa9cb3);
  stop-opacity: 0.39;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t3pao9bbb {
  fill: var(--svg-color--7c648f, #7c648f);
  d: path("M17.8 8.591c2.079 4.584 7.64 6.5 7.141 12.474c-.582 7.017-5.551 8.784-8.316 8.909a8.815 8.815 0 0 1-9.4-7.485C5.618 15.046 12.655 3.632 16.709 2A15.1 15.1 0 0 0 17.8 8.591m-.166 18.857a.42.42 0 0 0-.057-.327c-.593-1.1-5.81-1.645-6.907-1.752a8.3 8.3 0 0 0 1.635 1.3a7.8 7.8 0 0 0 2.814 1.041c.803.121 2.348.223 2.516-.263Z");
}

.tlofp4x_d {
  stop-color: var(--svg-color--6f567e, #6f567e);
  stop-opacity: 0.66;
}

</style>
