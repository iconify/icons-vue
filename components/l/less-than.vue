<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeizvibld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:less-than" /></template>
<style>
.eeizvibld {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.409 6.129L8.376 12l9.033 5.871q.062.04.115.092q.052.052.094.112t.071.129q.029.068.045.14t.016.146q.001.074-.013.147t-.041.141t-.067.131t-.092.115t-.112.094t-.129.071t-.14.045t-.146.016q-.074.001-.147-.013t-.141-.041t-.131-.067l-10-6.5q-.133-.087-.22-.22q-.04-.062-.067-.131q-.028-.068-.041-.141t-.013-.147t.016-.146t.045-.14t.071-.129t.094-.112t.115-.092l10-6.5q.125-.081.272-.108q.147-.028.293.003t.269.116q.123.084.204.209q.04.062.067.131q.028.068.041.141t.013.147q-.001.073-.016.146q-.016.072-.045.14t-.071.129t-.094.112q-.053.052-.115.092");
}

</style>
