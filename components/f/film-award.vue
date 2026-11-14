<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1i4ty4ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:film-award" /></template>
<style>
.k1i4ty4ac {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.497 4.093l.456 1.065q.177.411.622.451l1.154.105q1.07.096 1.402 1.119q.333 1.022-.476 1.729l-.872.763q-.337.295-.238.731l.257 1.13q.239 1.048-.631 1.68t-1.793.08l-.993-.593q-.385-.23-.769 0l-.995.593q-.922.552-1.792-.08t-.631-1.681l.257-1.129q.099-.436-.238-.731l-.872-.763q-.809-.707-.476-1.729q.332-1.023 1.403-1.119l1.152-.105q.446-.04.623-.451l.456-1.065q.423-.988 1.497-.988t1.497.988M12.75 16.75V14q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 13.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v2.75h-2q-1.036 0-1.768.732T6.75 19.25t.732 1.768t1.768.732h5.5q1.036 0 1.768-.732t.732-1.768t-.732-1.768t-1.768-.732z");
}

</style>
