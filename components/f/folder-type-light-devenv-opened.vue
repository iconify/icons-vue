<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f3a1ggjtf"/><path class="g6lpgsbkm"/><path class="xmjuprbtk"/><path class="eojsp7bni"/><path class="el_wwcjla"/><path class="v7_2lobzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-light-devenv-opened" /></template>
<style>
.el_wwcjla {
  fill: var(--svg-color--101010, #101010);
  d: path("M12.7 24.4H17v4.3h-4.3zm4.9 0h4.3v4.3h-4.3zm4.9 0h4.3v4.3h-4.3z");
}

.eojsp7bni {
  fill: var(--svg-color--425c82, #425c82);
  d: path("M22.5 19.5h4.3v4.3h-4.3zm4.9 0h4.3v4.3h-4.3z");
}

.f3a1ggjtf {
  fill: var(--svg-color--6d8ab5, #6d8ab5);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

.g6lpgsbkm {
  fill: var(--svg-color--425c82, #425c82);
  d: path("M22.5 14.6h4.3v4.3h-4.3z");
}

.v7_2lobzr {
  fill: var(--svg-color--425c82, #425c82);
  d: path("M27.4 24.4h4.3v4.3h-4.3z");
}

.xmjuprbtk {
  fill: var(--svg-color--101010, #101010);
  d: path("M17.6 19.5h4.3v4.3h-4.3z");
}

</style>
