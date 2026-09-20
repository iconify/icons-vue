<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="i47z94ida"/><path class="t3myz4byw"/><path class="l8cden4cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bread" /></template>
<style>
.i47z94ida {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M36 13.5c0-4.558-4.435-8.267-10-8.479V5H10v.021C4.435 5.233 0 8.942 0 13.5c0 1.861.747 3.576 2 4.976V31a4 4 0 0 0 4 4h24a4 4 0 0 0 4-4V18.476c1.253-1.4 2-3.115 2-4.976");
}

.l8cden4cd {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M21 13.5c0-3.461-3.538-6.291-8-6.489C12.835 7.004 10.668 7 10.5 7C5.806 7 2 9.91 2 13.5c0 1.595.754 3.053 2 4.184V30a3 3 0 0 0 3 3h9a3 3 0 0 0 3-3V17.679c1.244-1.131 2-2.586 2-4.179");
}

.t3myz4byw {
  fill: var(--svg-color--cc927a, #cc927a);
  d: path("M19 18.476h15v1.5H19z");
}

</style>
