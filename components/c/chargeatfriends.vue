<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b2myk7b3p"/><path class="ca_qaebfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chargeatfriends" /></template>
<style>
.b2myk7b3p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.67 8.928l5.171 4.96v9.8l-5.151-.058m-.02-14.694L5.5 13.887v9.802l5.195-.06m23.697-9.026h3.178s2.956.667 2.988 3.655h1.525s.938.651 0 1.589h-.667v1.176s1.112 1.271-.572 2.447v1.43s-.954 1.303-1.939 0v-1.303h-4.608m.603-8.994h-3.178s-2.956.667-2.988 3.655H27.21s-.938.651 0 1.589h.667v1.176s-1.112 1.271.572 2.447v1.43s.954 1.303 1.94 0v-1.303h4.608m-.639 2.485s.806 12.99-11.821 12.99m-11.783-12.99s-.806 12.99 11.821 12.99");
}

.ca_qaebfv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.067 14.38h-2.813v3.608h2.813l.004-3.604m14.663 3.874h11.824");
}

</style>
