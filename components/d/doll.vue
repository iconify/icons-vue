<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oscmabcnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:doll" /></template>
<style>
.oscmabcnk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 5.75q0-4 4-4q1.657 0 2.828 1.172Q16 4.093 16 5.75q0 4-4 4t-4-4M4.55 11.1l3.528 2.646l-1.722 4.02q-.53 1.237.211 2.361q.741 1.123 2.087 1.123h6.692q1.346 0 2.087-1.123q.741-1.124.211-2.361l-1.722-4.02L19.45 11.1q.119-.09.195-.218t.097-.276t-.015-.292t-.127-.264q-.044-.059-.099-.108q-.055-.05-.119-.087q-.063-.038-.133-.063q-.07-.024-.143-.034t-.147-.007t-.145.022t-.138.051t-.126.076l-3.241 2.431Q14.641 11 13.096 11h-2.192q-1.545 0-2.213 1.331L5.45 9.9q-.119-.09-.264-.127q-.144-.037-.292-.015t-.276.097t-.218.195t-.127.264t-.015.292q.021.148.097.276t.195.218");
}

</style>
