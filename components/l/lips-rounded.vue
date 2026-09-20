<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih-h3ma2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lips-rounded" /></template>
<style>
.ih-h3ma2v {
  fill: currentColor;
  d: path("M12.025 12q-2.35 0-4.612-.5T2.9 10.3q-.3-.1-.387-.413t.137-.537l3.4-3.4q.425-.425.988-.663t1.137-.237q.425 0 .863.138t.812.387l1.6 1.05q.25.175.55.175t.55-.175l1.6-1.05q.375-.25.813-.387t.862-.138q.575 0 1.138.238t.987.662l3.325 3.325q.225.225.15.538t-.375.437q-2.2.75-4.437 1.25t-4.588.5m-.675 7q-3.125 0-5.687-1.638T1.75 13q-.15-.3.075-.562T2.4 12.3q2.35.75 4.738 1.225T12 14q2.5 0 4.888-.513t4.737-1.287q.35-.125.588.138t.087.587q-1.325 2.75-3.912 4.413T12.65 19z");
}

</style>
