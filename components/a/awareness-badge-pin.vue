<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3as6mb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:awareness-badge-pin" /></template>
<style>
.q3as6mb-l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m6.376 7.695L9.632 9.928q-1.702-2.15.323-4.037q2.045-1.906 4.09 0q2.025 1.887.323 4.037l-1.496 2.519l2.773 4.67q.076.128.097.276t-.015.292q-.037.145-.126.264q-.09.12-.218.196t-.276.097t-.292-.015t-.264-.126t-.196-.218L12 13.916l-2.355 3.967q-.076.128-.196.218q-.119.089-.264.126q-.144.037-.292.015t-.276-.097t-.218-.196q-.089-.119-.126-.264q-.037-.144-.015-.292t.097-.276zM12 10.978l1.105-1.861q.028-.046.062-.088q.878-1.088-.144-2.041t-2.046 0q-1.022.953-.144 2.041q.034.042.062.088z");
}

</style>
