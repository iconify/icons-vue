<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wd2ph4bcy"/><path class="vqzgsgbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-fsharp2" /></template>
<style>
.vqzgsgbvy {
  fill: var(--svg-color--378bba, #378bba);
  d: path("M13.163 9.934H6.349v4.702h6.262v3.501H6.349v7.441H2V6.421h11.163z");
}

.wd2ph4bcy {
  fill: var(--svg-color--30b9db, #30b9db);
  d: path("M19.048 6.421h2.739V9.16h2.738V6.421h2.738V9.16H30v2.74h-2.737v2.737H30v2.739h-2.737v2.738h-2.738v-2.739h-2.736l.005 2.738H19.05v-2.739h-2.739v-2.742h2.739V11.9h-2.739V9.157h2.74Zm2.739 8.216h2.738V11.9h-2.738Z");
}

</style>
