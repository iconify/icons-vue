<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mv897jbch"/><path class="ry21rrbyl"/><path class="iuldd65qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-light-skill" /></template>
<style>
.iuldd65qy {
  stroke: var(--svg-color--fff, #fff);
  stroke-width: var(--svg-stroke-width--2-032px, 2.032px);
  d: path("m21.91 13.73l5.86 3.38v6.78l-5.86 3.38l-5.87-3.38v-6.78z");
}

.mv897jbch {
  fill: var(--svg-color--3e3e3e, #3e3e3e);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21zm0 4.2h-8.2l1.1-2.1h7.1z");
}

.ry21rrbyl {
  d: path("M21.91 10L31 15.25v10.5L21.91 31l-9.09-5.25v-10.5z");
}

</style>
