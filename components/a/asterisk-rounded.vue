<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obmxa61qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:asterisk-rounded" /></template>
<style>
.obmxa61qf {
  fill: currentColor;
  d: path("M11.643 19.857q-.143-.143-.143-.357v-6.292l-4.45 4.455q-.146.146-.347.156t-.367-.155t-.165-.357t.165-.357l4.456-4.45H4.5q-.213 0-.357-.143T4 12t.143-.357t.357-.143h6.292L6.337 7.05q-.146-.146-.156-.357q-.01-.21.156-.356q.146-.146.356-.137t.357.156l4.45 4.456V4.5q0-.213.143-.357T12 4t.357.143t.143.357v6.312l4.47-4.475q.146-.146.346-.137q.201.01.348.156t.146.337t-.146.338L13.188 11.5H19.5q.214 0 .357.143T20 12t-.143.357t-.357.143h-6.312l4.475 4.47q.146.146.146.346q0 .201-.146.348q-.146.165-.356.155t-.357-.155l-4.45-4.456V19.5q0 .214-.143.357T12 20t-.357-.143");
}

</style>
