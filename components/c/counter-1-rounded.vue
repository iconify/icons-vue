<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu7rfybun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:counter-1-rounded" /></template>
<style>
.gu7rfybun {
  fill: currentColor;
  d: path("M12 22q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22m-.5-13v7q0 .425.288.713T12.5 17t.713-.288T13.5 16V8q0-.425-.288-.712T12.5 7h-2q-.425 0-.712.288T9.5 8t.288.713T10.5 9z");
}

</style>
