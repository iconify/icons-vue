<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s1cv-9b1r"/><path class="scyoyu96f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:leaks" /></template>
<style>
.s1cv-9b1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.912 23.652c.564-1.665 1.168-3.373 1.114-5.313c-.114-4.108-4.78-7.22-8.06-7.205c-2.903.012-7.696 2.746-7.385 7.956c1.244 20.814 22.02 26.338 35.321 15.81q-7.93.921-12.335-4.069c2.109-.822 3.844-1.406 6.686-.492c3.939-4.62 7.27-9.312 7.178-14.41zm-6.375-9.538l1.166 3.784m1.425-2.643l-3.602 1.166");
}

.scyoyu96f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.82 11.412l3.589-3.518l.104 3.94l2.565-1.607l-1.587 4.26m1.535 3.852l15.29-6.117l-.856 6.117");
}

</style>
