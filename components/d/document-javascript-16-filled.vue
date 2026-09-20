<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="okkofozkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-javascript-16-filled" /></template>
<style>
.okkofozkg {
  fill: currentColor;
  d: path("M3.5 10a.503.503 0 0 1 .5.5v3A1.5 1.5 0 0 1 2.5 15A1.5 1.5 0 0 1 1 13.5V13a.503.503 0 0 1 .5-.5a.503.503 0 0 1 .5.5v.5a.503.503 0 0 0 .5.5a.503.503 0 0 0 .5-.5v-3a.503.503 0 0 1 .5-.5m3.06 0c.414 0 .811.164 1.104.457l.19.19a.5.5 0 1 1-.708.707l-.189-.19A.56.56 0 0 0 6.561 11h-.134a.427.427 0 0 0-.19.809l.974.488A1.427 1.427 0 0 1 6.573 15H6.44a1.56 1.56 0 0 1-1.103-.457l-.19-.19a.5.5 0 1 1 .708-.707l.189.19A.56.56 0 0 0 6.44 14h.134a.427.427 0 0 0 .19-.809l-.974-.488A1.427 1.427 0 0 1 6.427 10zM9 4.5A1.5 1.5 0 0 0 10.5 6H14v7.5a1.5 1.5 0 0 1-1.5 1.5H8.525c.191-.26.336-.553.41-.87a2.44 2.44 0 0 0-.255-1.76c.21-.272.324-.604.32-.943a2.44 2.44 0 0 0-.71-1.715A2.44 2.44 0 0 0 6.572 9H6.42a2.44 2.44 0 0 0-1.5.527q-.06.05-.116.109l-.048.047A1.47 1.47 0 0 0 4 9.09V2.5A1.5 1.5 0 0 1 5.5 1H9zm4.75.5H10.5a.5.5 0 0 1-.5-.5V1.25z");
}

</style>
