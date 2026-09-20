<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b3mea__lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-fastly" /></template>
<style>
.b3mea__lb {
  fill: var(--svg-color--ff282d, #ff282d);
  d: path("M18.23 5.55V3.52h.73V2h-6.03v1.52h.73v2.05a12.33 12.33 0 1 0 4.57-.02M16.34 24v-.71h-.71v.7A6.34 6.34 0 0 1 9.68 18h.72v-.71h-.7a6.34 6.34 0 0 1 5.94-5.95v.7h.72v-.71a6.33 6.33 0 0 1 5.98 5.97h-.71v.71h.71a6.36 6.36 0 0 1-6 6z");
}

</style>
