<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wpn-87bth"/><path class="yyemf82nl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:law-book-check" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wpn-87bth {
  d: path("M14.327 21.5H6q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T4.5 20V5q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165q.095-.077.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T7 2.5h12.5v10.773m0 7.9v.327h-.273");
}

.yyemf82nl {
  d: path("M4.5 20q0-.074.007-.147t.022-.146q.014-.072.036-.142q.021-.071.049-.139t.063-.133t.076-.126q.041-.062.087-.119q.047-.057.099-.109t.109-.099t.119-.087t.126-.076t.133-.063t.139-.049t.142-.036q.073-.015.146-.022T6 18.5h5.279M8.5 2.5v16m6.25-.5l2 2L21 15.75");
}

</style>
