<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8jfn5a8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:allergen-shellfish" /></template>
<style>
.q8jfn5a8a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m9.662 5.965v.001q.054.068.122.122q.062.049.132.084l.009.004q.038.018.076.032h.002q.12.042.247.042h.005q.041 0 .082-.005q.072-.008.142-.031l.02-.006q.038-.014.076-.032l.02-.01q.143-.074.243-.2v-.001h.001v-.001l4.749-5.998q.079-.1.12-.22q.042-.119.042-.246q0-2.346-1.646-3.837Q14.294 6.25 12 6.25T8.146 7.663Q6.5 9.154 6.5 11.5q0 .127.042.246q.041.12.12.22l4.749 5.999z");
}

</style>
