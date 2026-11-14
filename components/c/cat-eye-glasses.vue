<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiw74-bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cat-eye-glasses" /></template>
<style>
.xiw74-bov {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.779 7.304q2.365.946 7.471.946q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141T11 9v.042q.452-.104 1-.104t1 .104V9q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q5.106 0 7.471-.946q.187-.075.385-.046q.073.01.143.034q.07.025.133.063q.064.037.119.087t.099.108q.044.059.076.126q.032.066.051.138q.018.071.022.145t-.007.147l-.498 3.487q-.519 4.157-4.244 4.157H17q-4 0-4-4v-1.128q-.356-.184-1-.184t-1 .184v1.128q0 4-4 4h-.5q-3.725 0-4.244-4.157l-.498-3.487q-.011-.073-.007-.147t.022-.145q.019-.072.051-.138T1.9 7.55t.099-.108q.055-.05.119-.087q.063-.038.133-.063q.07-.024.143-.034q.198-.029.385.046");
}

</style>
