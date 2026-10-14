<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fh449-61a"/><path class="mjexvjb3s"/><path class="v1frnyhkl"/><path class="bv51jqr4p"/><path class="u_mqp6wan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-protobuf" /></template>
<style>
.bv51jqr4p {
  fill: var(--svg-color--4081ec, #4081ec);
  d: path("M10.03 25.23c0-.31 0-.31 2.2-3.28l6.94 9.04H14.2c-4.17-5.41-4.17-5.42-4.17-5.76");
}

.fh449-61a {
  fill: var(--svg-color--5ec894, #5ec894);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21zm0 4.2h-8.2l1.1-2.1h7.1z");
}

.mjexvjb3s {
  fill: var(--svg-color--d44235, #d44235);
  d: path("m12.23 21.95l1.86-2.54h5.08l-4.4 5.93h-2.54z");
}

.u_mqp6wan {
  fill: var(--svg-color--0f9855, #0f9855);
  d: path("M21.77 19.41h4.91c4.11 5.37 4.29 5.57 4.29 5.82c.01.24-.03.36-2.31 3.27z");
}

.v1frnyhkl {
  fill: var(--svg-color--f7bb07, #f7bb07);
  d: path("M26 25.06h2.66v3.44l-1.92 2.49h-4.97z");
}

</style>
