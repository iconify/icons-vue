<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-d866bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fencing-glove" /></template>
<style>
.a-d866bwo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.5 12.25H9.25q-.853 0-1.383.324q-.039-.056-.087-.104L4.598 9.288q-.443-.799.224-1.466t1.466-.224L8.72 10.03q.105.106.243.163t.287.057q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T10 9.5v-4q0-2.75 2.75-2.75q1.139 0 1.945.805q.805.806.805 1.945zm1.5.076V5.5q0-1.76-1.245-3.005T12.75 1.25T9.745 2.495T8.5 5.5v2.189L7.28 6.47q-.063-.063-.138-.11q-1.849-1.131-3.381.401t-.401 3.381q.047.075.11.138l3.25 3.25q.151.152.36.201q-.08.344-.08.769q0 .994.439 1.549q-.19.221-.344.504l-1.091 2q-.682 1.249.044 2.473t2.15 1.224h9.104q1.423 0 2.15-1.224t.044-2.473l-1.091-2q-.154-.283-.344-.504q.439-.555.439-1.549q0-1.837-1.5-2.174");
}

</style>
