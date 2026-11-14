<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqohchdhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:barista-apron" /></template>
<style>
.cqohchdhi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.641 3.641Q7.25 5.032 7.25 7v3.036l-2.585 1.293q-.104.052-.187.133l-.008.008l-2.5 2.5q-.106.105-.163.243t-.057.287t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l1.22-1.219V20q0 2.25 2.25 2.25h11q2.25 0 2.25-2.25v-6.189l1.22 1.219q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243l-2.499-2.5h-.001l-.008-.008q-.083-.081-.187-.133l-2.585-1.293V7q0-1.968-1.391-3.359T12 2.25T8.641 3.641m6.56 2.609H8.799Q9.15 3.75 12 3.75t3.201 2.5M8.25 16.75q0-2.5 2.5-2.5h2.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732T8.25 16.75");
}

</style>
