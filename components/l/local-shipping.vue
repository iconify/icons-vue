<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2-jhlieb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-shipping" /></template>
<style>
.i2-jhlieb {
  fill: currentColor;
  d: path("M3.837 18.356q-.76-.76-.76-1.856H1.692V6.616q0-.691.463-1.153T3.308 5h13.23v3.616h2.308l3.462 4.653V16.5h-1.616q0 1.096-.76 1.856q-.759.76-1.855.76t-1.856-.76t-.76-1.856H8.308q0 1.096-.76 1.856t-1.856.76t-1.856-.76m3.001-.71q.47-.471.47-1.146t-.47-1.145t-1.145-.47t-1.145.47t-.47 1.145t.47 1.145t1.145.47t1.146-.47m12.384 0q.47-.47.47-1.145t-.47-1.145t-1.145-.47t-1.145.47t-.47 1.145t.47 1.145t1.145.47t1.145-.47M16.538 13.5h4.712l-2.942-3.884h-1.77z");
}

</style>
