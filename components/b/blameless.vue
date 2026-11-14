<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihhz66bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blameless" /></template>
<style>
.ihhz66bvn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.779 4.804l-7.5-3Q12.144 1.75 12 1.75t-.279.054l-7.5 3q-.104.041-.191.112q-.088.07-.151.164q-.063.093-.096.2t-.033.22v6q0 7.209 7.949 10.687q.144.063.301.063t.301-.063Q20.25 18.709 20.25 11.5v-6q0-.112-.033-.22q-.033-.107-.096-.2t-.151-.164q-.087-.071-.191-.112M11.47 16.53l-3.5-3.5q-.038-.037-.07-.08q-1.691-2.255.302-4.248Q9.995 6.909 12 8.098q2.005-1.189 3.798.604q1.993 1.993.302 4.248q-.032.043-.07.08l-3.5 3.5q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094");
}

</style>
