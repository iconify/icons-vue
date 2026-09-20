<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zt6w-rb3p"/><path class="xqbhoxb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-toml" /></template>
<style>
.xqbhoxb2a {
  fill: var(--svg-color--7e7f7f, #7e7f7f);
  d: path("M2 2h6.2v3.09H5.34v21.8H8.2V30H2Zm28 28h-6.2v-3.09h2.86V5.11H23.8V2H30Z");
}

.zt6w-rb3p {
  d: path("M22.76 6.83v3.25h-5v15.09h-3.5V10.08h-5V6.83Z");
}

</style>
