<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="si7-5wbhy"/><path class="g6lpgsbkm"/><path class="xmjuprbtk"/><path class="eojsp7bni"/><path class="el_wwcjla"/><path class="v7_2lobzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-light-devenv" /></template>
<style>
.el_wwcjla {
  fill: var(--svg-color--101010, #101010);
  d: path("M12.7 24.4H17v4.3h-4.3zm4.9 0h4.3v4.3h-4.3zm4.9 0h4.3v4.3h-4.3z");
}

.eojsp7bni {
  fill: var(--svg-color--425c82, #425c82);
  d: path("M22.5 19.5h4.3v4.3h-4.3zm4.9 0h4.3v4.3h-4.3z");
}

.g6lpgsbkm {
  fill: var(--svg-color--425c82, #425c82);
  d: path("M22.5 14.6h4.3v4.3h-4.3z");
}

.si7-5wbhy {
  fill: var(--svg-color--4f6e9c, #4f6e9c);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
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
