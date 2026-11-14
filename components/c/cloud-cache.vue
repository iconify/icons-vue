<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7mfxegdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloud-cache" /></template>
<style>
.b7mfxegdd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 18.75q-1.968 0-3.359-1.391T2.25 14t1.391-3.359q1.195-1.194 2.815-1.363q1.467-3.889 5.794-3.889t5.794 3.889q1.62.169 2.815 1.363Q22.25 12.032 22.25 14q0 .926-.308 1.725q-.508-.685-1.323-.889q-.129-1.349-1.544-1.907q-1.7-.672-2.828.763l-.005.006l-1.96 2.484q-.95 1.202-.415 2.568zm10.226-4.281l.002-.003q.553-.704 1.388-.375q.835.33.756 1.222l-.011.129q-.018.225.135.392q.153.166.38.166q.885.001 1.257.805t-.203 1.479l-2.279 2.681q-.588.692-1.399.284q-.812-.407-.608-1.293l.066-.285q.038-.161-.066-.291q-.103-.13-.268-.13q-.888.001-1.276-.798q-.387-.799.163-1.496zm-.683 3.287q.775.061 1.275.69q.281.353.368.75l1.452-1.708q-.729-.077-1.246-.638q-.35-.381-.471-.841z");
}

</style>
