<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ctkv6abrz"/><path class="to4hxfb8o"/><path class="d0rxnz94z"/><path class="od-f37b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-guinea-bissau" /></template>
<style>
.ctkv6abrz {
  fill: var(--svg-color--00785e, #00785e);
  d: path("M22 54h32c6.627 0 10-4.925 10-11V33H22z");
}

.d0rxnz94z {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M22 10H10C3.373 10 0 14.925 0 21v22c0 6.075 3.373 11 10 11h12z");
}

.od-f37b1z {
  fill: var(--svg-color--25333a, #25333a);
  d: path("m19.06 29.357l-6.303.016l-1.95-6.379l-1.945 6.379l-6.308-.016l5.109 3.883l-1.976 6.334l5.124-3.936l5.132 3.936l-1.982-6.334z");
}

.to4hxfb8o {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M54 10H22v23h42V21c0-6.075-3.373-11-10-11");
}

</style>
