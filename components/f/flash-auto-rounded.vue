<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbxzayc7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flash-auto-rounded" /></template>
<style>
.pbxzayc7e {
  fill: currentColor;
  d: path("m16.533 8.392l-.914 2.325q-.055.123-.156.203t-.25.08q-.24 0-.366-.187q-.126-.188-.04-.404l2.816-7.244q.086-.234.293-.377t.461-.161q.26-.02.476.141t.322.395l2.86 7.233q.086.235-.047.42q-.132.184-.373.184q-.148 0-.261-.07t-.17-.218l-.913-2.32zm.296-.8h3.134l-1.536-4.019h-.089zM6.12 17.265q-.12-.16-.12-.376V13H5q-.671 0-1.143-.472q-.473-.472-.473-1.144V4.617q0-.672.473-1.144Q4.329 3 5 3h3.83q.686 0 1.125.5q.44.5.259 1.116L9 8.789h1.606q.727 0 1.068.636q.342.637-.068 1.252l-4.5 6.56q-.131.186-.31.242q-.18.056-.367 0t-.308-.215");
}

</style>
