<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz-c6r61p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:attribution-sharp" /></template>
<style>
.nz-c6r61p {
  fill: currentColor;
  d: path("M11.058 18.077h1.884v-4.116h1.308v-5h-4.5v5h1.308zM8.5 20.29q-1.642-.711-2.86-1.93T3.71 15.5T3 11.997t.71-3.5T5.64 5.64T8.5 3.71Q10.142 3 12.003 3q1.86 0 3.5.71q1.64.711 2.858 1.93t1.929 2.857q.71 1.64.71 3.5t-.71 3.503q-.711 1.642-1.93 2.86t-2.857 1.93t-3.5.71t-3.503-.71m4.344-12.33q.348-.348.348-.844q0-.497-.348-.845T12 5.923t-.844.348t-.348.845q0 .496.348.844t.844.348t.844-.348");
}

</style>
