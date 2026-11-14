<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjsja7qvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:indoor-garden" /></template>
<style>
.xjsja7qvo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 10.221Q2.5 9.879 2.5 5.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q2.532 0 3.782 1.218Q7.907 3.25 11.5 3.25q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 4.359-4 4.718v2.532h.008q1.032 0 1.705.782q.674.782.521 1.802l-.3 2q-.033.221-.088.416h3.808q-.055-.195-.088-.416l-.3-2q-.153-1.02.521-1.802q.102-.119.213-.22V6.5q0-2.25 2.25-2.25t2.25 2.25v5.312q.111.101.214.22q.673.782.52 1.802l-.3 2q-.033.221-.088.416h1.154q2 0 2 2t-2 2H3.75q-2 0-2-2q0-.828.586-1.414t1.414-.586h1.154q-.055-.195-.088-.416l-.3-2q-.153-1.02.521-1.802q.673-.782 1.705-.782h.008zm10.5 1.029V6.5q0-.75-.75-.75t-.75.75v4.75z");
}

</style>
