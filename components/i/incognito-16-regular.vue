<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uj8v6ablr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:incognito-16-regular" /></template>
<style>
.uj8v6ablr {
  fill: currentColor;
  d: path("M12 8a3 3 0 1 1-2.958 3.5H6.958a3 3 0 1 1 0-1h2.084A3 3 0 0 1 12 8M4 9a2 2 0 1 0 0 4a2 2 0 0 0 0-4m8 0a2 2 0 1 0 0 4a2 2 0 0 0 0-4M8 5.5a45 45 0 0 1 6.58.507h.003a.5.5 0 0 1-.166.986h-.002c-.164-.037-.336-.053-.503-.076A44 44 0 0 0 8 6.5a44 44 0 0 0-6.289.473c-.072.01-.126.02-.126.02h-.002a.5.5 0 0 1-.166-.986h.003l.138-.023l.39-.057A45 45 0 0 1 8 5.5M10.883 2a1.5 1.5 0 0 1 1.342.83l.723 1.447a.5.5 0 0 1-.894.447l-.724-1.448A.5.5 0 0 0 10.883 3H5.119a.5.5 0 0 0-.447.276l-.725 1.448a.5.5 0 0 1-.893-.447l.723-1.448A1.5 1.5 0 0 1 5.12 2zm3.697 4.007l-.007-.002l.01.002");
}

</style>
