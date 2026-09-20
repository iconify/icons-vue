<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="q8c3_nb9m"/><path class="rlksh5ztc"/><path class="k2twsacsf"/><path class="b64qd5brp"/><path class="k6ik8hqgs"/><path class="qunni9aon"/><path class="nb8n3db5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-vapor" /></template>
<style>
.b64qd5brp {
  fill: var(--svg-color--25c4f2, #25c4f2);
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.169 20H9.619l5.275-11Z");
}

.k2twsacsf {
  fill: var(--svg-color--25c4f2, #25c4f2);
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20.169 20h10.55l-5.275 11Z");
}

.k6ik8hqgs {
  fill: var(--svg-color--25c4f2, #25c4f2);
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M30.718 20h-10.55l5.276-11Z");
}

.nb8n3db5l {
  fill: var(--svg-color--25c4f2, #25c4f2);
  d: path("M35.99 8H25.44a1 1 0 0 0-.9.568l-4.373 9.12l-4.373-9.12A1 1 0 0 0 14.89 8H4.34a1 1 0 0 0-.9 1.432l10.55 22a1 1 0 0 0 .9.568h10.55a1 1 0 0 0 .9-.576L36.892 9.432A1 1 0 0 0 35.99 8m-21.1 3.313L18.58 19h-7.372ZM5.934 10h7.372L9.62 17.687Zm8.959 18.687L11.207 21h7.372l-3.685 7.685ZM16.483 30l3.686-7.687L23.855 30Zm8.961-1.313L21.758 21h7.372ZM21.758 19l3.686-7.687L29.13 19Zm8.96-1.313L27.032 10h7.373Z");
}

.q8c3_nb9m {
  fill: var(--svg-color--e9f9fd, #e9f9fd);
  fill-opacity: var(--svg-fill-opacity--0-1, 0.1);
  d: path("M4.345 9H14.9L9.618 20Zm21.1 0h10.55l-5.277 11Z");
}

.qunni9aon {
  fill: var(--svg-color--25c4f2, #25c4f2);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M25.444 31h-10.55l5.275-11Z");
}

.rlksh5ztc {
  fill: var(--svg-color--25c4f2, #25c4f2);
  fill-opacity: var(--svg-fill-opacity--0-22, 0.22);
  d: path("M9.62 20h10.549l-5.275 11Z");
}

</style>
