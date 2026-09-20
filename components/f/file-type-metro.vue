<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k3ytwrbtw"/><path class="jprroxbqm"/><path class="b22q9hbiz"/><path class="s1035euyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-metro" /></template>
<style>
.b22q9hbiz {
  fill: var(--svg-color--ef4242, #ef4242);
  d: path("M15.997 25.31a1.3 1.204 0 0 1-.65-.162l-9.719-5.195a1.303 1.206 0 0 1-.652-1.045V8.518a1.303 1.206 0 0 1 1.988-1.03l9.043 5.079l9.043-5.08a1.303 1.206 0 0 1 1.976 1.03v10.391a1.3 1.204 0 0 1-.65 1.045l-9.729 5.195a1.31 1.214 0 0 1-.65.162m-8.418-7.1l8.424 4.5l8.424-4.5v-7.55l-7.74 4.354a1.299 1.203 0 0 1-1.352 0L7.593 10.66Z");
}

.jprroxbqm {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.997 27.697a2.178 2.017 0 0 1-1.081-.254L6.2 22.783a2.259 2.092 0 0 1-1.08-1.732v-9.319A2.259 2.092 0 0 1 6.2 10l8.718-4.66a2.302 2.131 0 0 1 2.155 0L25.788 10a2.255 2.088 0 0 1 1.08 1.732v9.319a2.257 2.09 0 0 1-1.078 1.732l-8.714 4.66a2.17 2.01 0 0 1-1.079.254m-8.56-6.728l8.56 4.577l8.56-4.577v-9.155l-8.56-4.577l-8.56 4.577Z");
}

.k3ytwrbtw {
  fill: var(--svg-color--ef4242, #ef4242);
  d: path("M2 11.23c0-1.364 1.046-3.032 2.314-3.712l9.368-5.008c1.273-.68 3.355-.68 4.629 0l9.368 5.008c1.273.68 2.315 2.358 2.315 3.712v10.017c0 1.36-1.042 3.03-2.315 3.711l-9.368 5.008c-1.274.68-3.356.68-4.63 0l-9.367-5.008C3.042 24.278 2 22.6 2 21.247Z");
}

.s1035euyf {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.871 21.588h-2.313V13.1l-7.961 4.477a1.152 1.067 0 0 1-1.201 0L7.436 13.1v8.488H5.121V11.195a1.16 1.074 0 0 1 1.763-.907l9.113 5.12l9.117-5.129a1.158 1.072 0 0 1 1.763.907Z");
}

</style>
