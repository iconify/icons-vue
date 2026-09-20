<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGoacEOdNK" x1="17.244" x2="14.968" y1="367.597" y2="341.994" gradientTransform="translate(0 -338)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".01" class="k51plyemn"/><stop offset=".09" class="j5_9vubly"/><stop offset=".2" class="p_u9cx31r"/><stop offset=".32" class="sa3y90bbo"/><stop offset=".5" class="ye2y653dm"/><stop offset="1" class="j8s9d1bzz"/></linearGradient></defs><path class="kav95jbgv"/><path class="qy5e9vere"/><path fill="url(#SVGoacEOdNK)" class="mnn-osbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-eex" /></template>
<style>
.j5_9vubly {
  stop-color: var(--svg-color--e44f26, #e44f26);
  stop-opacity: 0.39;
}

.j8s9d1bzz {
  stop-color: var(--svg-color--e44f26, #e44f26);
}

.k51plyemn {
  stop-color: var(--svg-color--e44f26, #e44f26);
  stop-opacity: 0.04;
}

.kav95jbgv {
  fill: var(--svg-color--7c648f, #7c648f);
  d: path("M17.8 8.591c2.079 4.584 7.64 6.5 7.141 12.474c-.582 7.017-5.551 8.784-8.316 8.909a8.815 8.815 0 0 1-9.4-7.485C5.618 15.046 12.655 3.632 16.709 2A15.1 15.1 0 0 0 17.8 8.591m-.166 18.857a.42.42 0 0 0-.057-.327c-.593-1.1-5.81-1.645-6.907-1.752a8.3 8.3 0 0 0 1.635 1.3a7.8 7.8 0 0 0 2.814 1.041c.8.121 2.348.223 2.516-.263Z");
}

.mnn-osbuw {
  d: path("M17.385 9.921C20.369 14 24.319 13.7 25 19.641c.094 6.923-3.6 9.283-6.237 9.948c-4.5 1.279-8.514-.645-10.094-5c-3.035-7 2.651-18.514 6.31-20.915a15.1 15.1 0 0 0 2.37 6.237Z");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.p_u9cx31r {
  stop-color: var(--svg-color--e44f26, #e44f26);
  stop-opacity: 0.66;
}

.qy5e9vere {
  fill: var(--svg-color--26003d, #26003d);
  d: path("M18.248 10.618c4.47 4.823 6.445 4.979 6.237 10.478c-.249 6.476-4.543 8.191-7.058 8.42c-4.2.551-7.495-1.528-8.358-5.686c-1.757-6.767 3.909-17.807 7.568-19.47a15.3 15.3 0 0 0 1.621 6.24Z");
  opacity: var(--svg-opacity--0-25, 0.25);
}

.sa3y90bbo {
  stop-color: var(--svg-color--e44f26, #e44f26);
  stop-opacity: 0.86;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.ye2y653dm {
  stop-color: var(--svg-color--e44f26, #e44f26);
  stop-opacity: 0.97;
}

</style>
