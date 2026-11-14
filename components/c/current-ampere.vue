<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f46ug_b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:current-ampere" /></template>
<style>
.f46ug_b1i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m6.051 4.228q-.027.069-.04.142q-.012.073-.011.146q.002.074.018.146t.046.14q.029.068.072.128q.042.061.095.112q.054.051.116.091q.062.039.131.066q.139.054.288.051q.15-.003.286-.064q.137-.06.24-.167t.157-.247l.981-2.522h3.64l.981 2.522q.054.139.157.247t.24.167q.136.061.286.064t.288-.051t.247-.157q.107-.103.167-.24q.061-.136.064-.286t-.051-.288l-3.5-9q-.057-.147-.169-.258q-.111-.112-.258-.169q-.069-.027-.142-.04q-.073-.012-.146-.011q-.074.002-.146.018t-.14.046q-.068.029-.128.072q-.061.042-.112.095q-.051.054-.091.116q-.039.062-.066.131zm2.962-3.478h2.474L12 9.569z");
}

</style>
