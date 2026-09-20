<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="n_3byhb4k"/><path class="t5n9acbem"/><path class="w3t9mubyb"/><path class="pj-we2bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bell-pepper" /></template>
<style>
.n_3byhb4k {
  fill: var(--svg-color--3e721d, #3e721d);
  d: path("M16 10c-1-3 0-8 4-9s6 1 6 2s-1 3-2 2s-3-1-4 1s0 4 0 4z");
}

.pj-we2bqk {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M24.971 22.431C24.971 29.887 24.05 35 18 35s-6.971-5.113-6.971-12.569S6.049 8 18 8s6.971 6.975 6.971 14.431");
}

.t5n9acbem {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M23.945 21.966c0 7.199-3.092 8.978-11 12.034c-7.761 3-6.761-5-8-12.034c-.522-2.964-1.02-3.781-1.562-5.987c-.753-3.072-.58-7.048 4.562-7.048c8.837 0 16 5.836 16 13.035");
}

.w3t9mubyb {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M12.055 21.966c0 7.199 3.092 8.978 11 12.034c7.761 3 6.761-5 8-12.034c.522-2.964 1.02-3.781 1.562-5.987c.754-3.071.581-7.048-4.562-7.048c-8.837 0-16 5.836-16 13.035");
}

</style>
