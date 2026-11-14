<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klfc3jbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:globe-europe-africa" /></template>
<style>
.klfc3jbss {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m8.65-2.95q-.073.097-.112.213q-.038.115-.038.237v1q0 .227.126.416l1 1.5q.083.125.208.208l1.205.803l.215 2.148q.012.12.061.23l1 2.25q.096.216.299.338q.063.038.133.063t.143.036t.146.007q.074-.003.146-.021t.138-.05q.067-.031.126-.075q.06-.044.109-.099q.05-.055.088-.118l.75-1.25q.029-.048.051-.1l1.745-4.241l.75-1.75l.007-.016q.028-.069.041-.142t.013-.146q-.001-.074-.016-.146q-.016-.073-.045-.14t-.071-.129t-.094-.113t-.115-.092q-.062-.04-.13-.067l-.915-.366l-.646-2.154q-.017-.057-.043-.111t-.061-.103q-.034-.05-.076-.093t-.09-.079q-.049-.036-.102-.063t-.11-.047t-.117-.028q-.059-.01-.119-.01h-3.5q-.087 0-.172.02t-.163.059q-.079.039-.146.095t-.119.126z");
}

</style>
