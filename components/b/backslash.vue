<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv6inubfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:backslash" /></template>
<style>
.mv6inubfx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.646 3.12l10 17q.038.063.062.133q.025.07.035.143t.006.147t-.023.145t-.051.138t-.076.126q-.045.059-.1.108t-.119.086q-.063.038-.133.062q-.07.025-.143.035t-.147.006t-.145-.023t-.138-.051t-.126-.076q-.059-.045-.108-.1t-.086-.119l-10-17q-.076-.128-.097-.276q-.02-.148.017-.292q.037-.145.127-.264t.219-.194q.063-.038.133-.062q.07-.025.143-.035t.147-.006t.145.023q.072.019.138.051t.126.076q.059.045.108.1t.086.119");
}

</style>
