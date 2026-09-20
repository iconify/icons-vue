<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGyoFAClZP" x1="0%" x2="99.996%" y1="36.301%" y2="64.611%"><stop offset="0%" class="xgxshwb6j"/><stop offset="100%" class="jjq_szb_f"/></linearGradient><linearGradient id="SVGnuFxjeJW" x1="102.837%" x2="-5.655%" y1="70.777%" y2="28.962%"><stop offset="0%" class="eloaaccms"/><stop offset="100%" class="vc--wpv5i"/></linearGradient><linearGradient id="SVGX0cLLd2o" x1="49.941%" x2="23.669%" y1="69.215%" y2="32.86%"><stop offset="0%" class="eloaaccms"/><stop offset="100%" class="vc--wpv5i"/></linearGradient></defs><path fill="url(#SVGyoFAClZP)" class="rrk1jfd4z"/><path fill="url(#SVGnuFxjeJW)" class="mohhrcbzh"/><path fill="url(#SVGX0cLLd2o)" class="lma78cgdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:apidog-icon" /></template>
<style>
.eloaaccms {
  stop-color: var(--svg-color--99c2ff, #99c2ff);
}

.jjq_szb_f {
  stop-color: var(--svg-color--73f, #73f);
}

.lma78cgdp {
  d: path("M77.117 253.864a28.2 28.2 0 0 1-9.184-6.12a28.185 28.185 0 0 1 .064-39.864l20.015-19.96l.504-.44c21.959-21.395 56.966-21.395 78.925 0l.504.44l20.015 19.96c10.932 11.035 10.875 28.835-.128 39.8c-11.014 11.006-28.853 11.035-39.902.064l-20.016-19.968l-19.95 19.96A28.3 28.3 0 0 1 87.947 256a28.2 28.2 0 0 1-10.831-2.136");
}

.mohhrcbzh {
  d: path("M178.712 2.136a28.1 28.1 0 0 1 9.184 6.12a28.185 28.185 0 0 1-.064 39.864l-20 19.96l-.503.44c-21.958 21.404-56.975 21.404-78.933 0l-.504-.44l-20.015-19.96c-10.934-11.033-10.88-28.833.12-39.8C79.011-2.686 96.85-2.715 107.9 8.256l20.015 19.968l19.952-19.968A28.3 28.3 0 0 1 167.88 0a28.2 28.2 0 0 1 10.84 2.136z");
}

.rrk1jfd4z {
  d: path("M198.391 180.368L194 175.984l-.816-.752a93.67 93.67 0 0 0-65.318-26.504a93.67 93.67 0 0 0-65.309 26.504l-.568.56l-4.327 4.384l-9.288 9.264a28.24 28.24 0 0 1-20.08 8.384a28.33 28.33 0 0 1-20.006-8.264A28.2 28.2 0 0 1 0 169.6c0-7.49 2.983-14.672 8.288-19.96l20.007-19.96l-19.76-19.656A28.23 28.23 0 0 1 0 89.824a28.2 28.2 0 0 1 8.288-19.96c11.06-11.033 28.962-11.033 40.022 0L62.805 84.32a93.75 93.75 0 0 0 65.317 26.48c24.4 0 47.838-9.504 65.31-26.48a3 3 0 0 1 .632-.632l8.215-8.256l5.464-5.384a27.97 27.97 0 0 1 19.951-8.256a28.3 28.3 0 0 1 20 8.264a28.185 28.185 0 0 1 6.119 30.864a27.8 27.8 0 0 1-6.296 9.176l-19.823 19.776l19.823 19.776a28.04 28.04 0 0 1 8.472 20.144a28.2 28.2 0 0 1-8.288 19.952c-11.038 11.026-28.92 11.026-39.958 0l-9.416-9.376z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.xgxshwb6j {
  stop-color: var(--svg-color--3bf, #3bf);
}

</style>
