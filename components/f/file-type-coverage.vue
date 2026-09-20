<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="od9n3lqic"/><path class="q6texabga"/><path class="mq_ux18eb"/><path class="t93x6vb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-coverage" /></template>
<style>
.mq_ux18eb {
  fill: var(--svg-color--00a302, #00a302);
  d: path("M10.53 2.45V22.1h10.21V2.45zm15.35 6.78v4.18h3.17V9.23zM21.33 14v5.66h7.72V14zm-3.17 8.57v5.66h2.58v-5.66zm6.6.3v4.2h4.3v-4.2zm-3.43 3.58v1.78h3.18v-1.78zm4.8.9v2.11h2.78v-2.12h-2.77z");
}

.od9n3lqic {
  fill: var(--svg-color--ffebe3, #ffebe3);
  d: path("M2.44 2h27.11v28H2.44z");
}

.q6texabga {
  fill: var(--svg-color--f20, #f20);
  d: path("M2.89 2.45v12.44H10V2.45zm18.44 6.78v4.18h4.19V9.23zm0 10.73v2.52h4.19v-2.52zm4.55 0v2.52h3.17v-2.52zm-15.35 2.62v6.93h7.32v-6.93zm10.8.3v3.18h3.18v-3.17h-3.18z");
}

.t93x6vb_y {
  fill: var(--svg-color--f9ff16, #f9ff16);
  d: path("M21.33 2.45v6.22h7.72V2.45zm-18.44 13V29.5H10V15.45zM24.77 27.3v.93h1.1v-.93zm-6.61 1.27v.93h7.72v-.93z");
}

</style>
