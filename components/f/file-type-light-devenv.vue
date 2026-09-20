<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fphcs6mir"/><path class="k0jhptbni"/><path class="lvbfpcbmy"/><path class="wkxfu1bmu"/><path class="qrtq8n_9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-devenv" /></template>
<style>
.fphcs6mir {
  fill: var(--svg-color--425c82, #425c82);
  d: path("M16.4 5.6h6.4V12h-6.4z");
}

.k0jhptbni {
  fill: var(--svg-color--101010, #101010);
  d: path("M9.2 12.8h6.4v6.4H9.2z");
}

.lvbfpcbmy {
  fill: var(--svg-color--425c82, #425c82);
  d: path("M16.4 12.8h6.4v6.4h-6.4zm7.2 0H30v6.4h-6.4z");
}

.qrtq8n_9a {
  fill: var(--svg-color--425c82, #425c82);
  d: path("M23.6 20H30v6.4h-6.4z");
}

.wkxfu1bmu {
  fill: var(--svg-color--101010, #101010);
  d: path("M2 20h6.4v6.4H2zm7.2 0h6.4v6.4H9.2zm7.2 0h6.4v6.4h-6.4z");
}

</style>
