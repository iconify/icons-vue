<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q-x_g4bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-elm2" /></template>
<style>
.q-x_g4bsi {
  fill: var(--svg-color--34495e, #34495e);
  d: path("m16 15.232l6.051-6.051H9.949zM2.768 2l6.095 6.095h13.248L16.016 2zm14 14l6.624-6.624l6.594 6.593l-6.625 6.625zM30 14.448V2H17.552zM15.232 16L2 2.768v26.464zm8.898 7.362l5.87 5.87v-11.74zM16 16.768L2.768 30h26.464z");
}

</style>
