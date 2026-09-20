<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fphcs6mir"/><path class="zh329rbhh"/><path class="lvbfpcbmy"/><path class="fll2mdbeg"/><path class="qrtq8n_9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-devenv" /></template>
<style>
.fll2mdbeg {
  fill: var(--svg-color--fbfbfb, #fbfbfb);
  d: path("M2 20h6.4v6.4H2zm7.2 0h6.4v6.4H9.2zm7.2 0h6.4v6.4h-6.4z");
}

.fphcs6mir {
  fill: var(--svg-color--425c82, #425c82);
  d: path("M16.4 5.6h6.4V12h-6.4z");
}

.lvbfpcbmy {
  fill: var(--svg-color--425c82, #425c82);
  d: path("M16.4 12.8h6.4v6.4h-6.4zm7.2 0H30v6.4h-6.4z");
}

.qrtq8n_9a {
  fill: var(--svg-color--425c82, #425c82);
  d: path("M23.6 20H30v6.4h-6.4z");
}

.zh329rbhh {
  fill: var(--svg-color--fbfbfb, #fbfbfb);
  d: path("M9.2 12.8h6.4v6.4H9.2z");
}

</style>
