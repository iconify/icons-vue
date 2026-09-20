<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjqpqbbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drive-export-outline" /></template>
<style>
.pjqpqbbpi {
  fill: currentColor;
  d: path("m16.9 21.789l-.688-.689l3.575-3.6H16.5v-1h5v5h-1v-3.292zM7.044 19h5.445l-3.797-6.5H5.963l-1.382 2.352q-.389.652-.376 1.391t.376 1.373q.363.651 1.028 1.018q.664.366 1.435.366M12 16.173l2.162-3.673H9.839zM6.537 11.5h8.198l1.342-2.289l-1.658-2.807q-.388-.633-1.028-1.019Q12.752 5 12 5q-.771 0-1.423.376t-1.04 1.028zm6.398 8.5h-5.89q-1.053 0-1.94-.504q-.886-.504-1.409-1.38q-.523-.877-.523-1.885t.523-1.885l4.981-8.442q.523-.877 1.41-1.39T12 4t1.904.514t1.4 1.39l3.925 6.654q-.292-.054-.607-.075q-.314-.021-.606.02l-1.366-2.316l-2.75 4.707q-.57.781-.843 1.731t-.274 2.021q0 .346.039.692q.04.346.113.662m3.715-9.813");
}

</style>
