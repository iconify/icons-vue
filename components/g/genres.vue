<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxjuv3sra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:genres" /></template>
<style>
.gxjuv3sra {
  fill: currentColor;
  d: path("M12.125 17.125Q13 16.25 13 15V8h3V6h-4.5v6.4q-.35-.2-.725-.3T10 12q-1.25 0-2.125.875T7 15t.875 2.125T10 18t2.125-.875M12 22q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
