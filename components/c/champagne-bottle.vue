<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0vq9cbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:champagne-bottle" /></template>
<style>
.e0vq9cbte {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 1.75q-1.75 0-1.75 1.75T13 5.25t1.75-1.75T13 1.75m8.164 1.086q.586.586.586 1.414q0 .829-.586 1.414q-.585.586-1.414.586t-1.414-.586q-.586-.585-.586-1.414t.586-1.414t1.414-.586t1.414.586M18.14 8.111q0-.932-.659-1.591h-.001q-.659-.66-1.591-.66t-1.591.66l-1.414 1.413q-.471.471-.606 1.081q-.627-.203-1.339-.203q-1.761 0-3.005 1.245l-2.828 2.828q-1.245 1.244-1.245 3.005t1.245 3.005q1.244 1.245 3.005 1.245t3.005-1.245l2.828-2.828q1.245-1.244 1.245-3.005q0-.712-.203-1.339q.61-.135 1.08-.606l1.414-1.414q.66-.659.66-1.591m1.11 2.389q0-1.75 1.75-1.75t1.75 1.75T21 12.25t-1.75-1.75");
}

</style>
