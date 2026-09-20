<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va16a7f8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:attribution-rounded" /></template>
<style>
.va16a7f8j {
  fill: currentColor;
  d: path("M12 8.962q-1.267 0-1.759.295q-.491.295-.491.797v3.495q0 .17.121.292q.121.12.283.12h.904v3.174q0 .396.272.669t.666.273t.67-.273t.276-.67v-3.172h.904q.162 0 .283-.121q.121-.122.121-.283v-3.504q0-.502-.491-.797q-.492-.295-1.759-.295m-3.497 11.33q-1.64-.707-2.864-1.931t-1.931-2.864T3 11.995t.71-3.5T5.64 5.64t2.862-1.93T12.005 3t3.498.71t2.858 1.93t1.929 2.855t.71 3.5t-.71 3.505t-1.93 2.86t-2.855 1.93t-3.5.71t-3.502-.707M12.844 7.96q.348-.348.348-.844q0-.497-.348-.845T12 5.923t-.844.348t-.348.845t.348.844t.844.348t.844-.348");
}

</style>
