<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x55yb_gfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kau" /></template>
<style>
.x55yb_gfy {
  fill: var(--svg-color--857550, #857550);
  d: path("m12.29 9.387l-3.484 3.484l4.715 7.142a2.5 2.5 0 0 0 2.02.987H21a11 11 0 0 1-2.323-2.323zM3 3h5.226v10.097l-5.226 5zm10.452 0h4.645L13.45 7.645z");
}

</style>
