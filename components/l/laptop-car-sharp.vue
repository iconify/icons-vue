<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tykpfx08v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:laptop-car-sharp" /></template>
<style>
.tykpfx08v {
  fill: currentColor;
  d: path("M10.23 21v-5.513l1.459-4.218h7.853L21 15.487V21h-1v-1.5h-8.77V21zm1.197-6.23h8.377l-.894-2.616h-6.59zm1.765 3.25q.367 0 .626-.26q.259-.258.259-.626q0-.367-.259-.625q-.258-.259-.626-.259t-.626.259t-.258.625t.258.626q.259.26.626.26m4.847 0q.367 0 .626-.26q.258-.258.258-.626q0-.367-.258-.625q-.26-.259-.626-.259t-.627.259q-.258.258-.258.625q0 .368.258.626q.26.26.626.26M2 19v-1.5h2V5h15v3.885H9.994L7.846 15.05V19z");
}

</style>
